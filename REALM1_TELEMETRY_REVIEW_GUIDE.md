# Realm 1 Telemetry Review Guide

Status: public local-telemetry and redaction guide for the QA/legal checklist. It does **not** approve privacy wording by itself.

The review build may write optional local JSONL playtest events. No network analytics are sent.

## Where it lives

The in-game path is:

```text
user://telemetry_aftertimes.jsonl
```

On Linux, `user://` usually resolves under:

```text
~/.local/share/godot/app_userdata/The AfterTimes/
```

On Windows, it is usually under:

```text
%APPDATA%\Godot\app_userdata\The AfterTimes\
```

If the folder is hard to find, search for `telemetry_aftertimes.jsonl` after one death, room build, or reactor completion.

## JSONL shape

Each line is one JSON object:

```json
{"event":"room_built","timestamp":"2026-07-03T18:00:00","ticks_msec":123456,"payload":{"realm_id":"aftertimes","room_type":"storage","grid_x":0,"grid_y":0,"room_count":3}}
```

Top-level fields:

- `event`: event name.
- `timestamp`: local event timestamp string.
- `ticks_msec`: local runtime tick count.
- `payload`: gameplay details for that event.

## Current event names

- `player_death` — includes `realm_id`, `world_seed`, `position`, and `radiation_meter`.
- `room_built` — includes `realm_id`, `room_type`, room position, source if a cave conversion, and `room_count`.
- `reactor_completed` — includes `realm_id`, `room_count`, and `npc_count`.

## Safe-to-share example snippets

These examples are sanitized. Keep only the lines relevant to a bug or review note.

```jsonl
{"event":"room_built","timestamp":"2026-07-03T18:00:00","ticks_msec":123456,"payload":{"realm_id":"aftertimes","room_type":"generator","grid_x":1,"grid_y":0,"room_count":6}}
{"event":"reactor_completed","timestamp":"2026-07-03T18:12:00","ticks_msec":654321,"payload":{"realm_id":"aftertimes","room_count":9,"npc_count":3}}
```

## Redact before posting

Do not post:

- Local filesystem paths with usernames, home folders, drive letters, or machine names.
- Full save files.
- Private account, tax, payout, platform dashboard, or unreleased credential data.
- Crash logs that include tokens, private paths, or machine-identifying details.

If a path is useful, replace the private part:

```text
/home/<user>/.local/share/godot/app_userdata/The AfterTimes/telemetry_aftertimes.jsonl
C:\Users\<user>\AppData\Roaming\Godot\app_userdata\The AfterTimes\telemetry_aftertimes.jsonl
```

## What to attach to review issues

For public QA feedback, attach only what helps explain the result:

- Last 5-20 relevant JSONL lines.
- Exact visible game text at the blocker.
- Screenshot or short video if comfortable.
- OS, hardware, input device, build zip SHA, and whether outside help was used.

Submit QA verdicts here:

<https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=playtest_report.yml>

Submit legal/store privacy verdicts here:

<https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=release_legal_store_review.yml>
