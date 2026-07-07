# Realm 1 Public Playtest Guide

Source guide date: 2026-06-18  
Public support copy: 2026-07-07
Build target: Realm 1 / **The AfterTimes** public Linux review package  
Status: **pre-QA playtest candidate, not ship-ready**

Current scope note, 2026-07-07: this public guide targets the source-fresh repo-hosted Linux review package linked below. The GitHub Release asset `realm1-review-a5392e7c` is superseded for new review until release-asset publication catches up. Windows/macOS/web/mobile are not part of this public packet.

Use this guide to test the first-chapter loop: choose a survivor, explore the
irradiated surface, find/enter the bunker, build rooms, recruit specialists,
craft reactor parts, steady the Geothermal Reactor, save, quit, and continue.

## Build identity

Public review package:

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-1c6591fb.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-1c6591fb.zip>
- Public repo-hosted package proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_REPO_DOWNLOAD_1C6591FB.md>
- Superseded GitHub Release page: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Zip SHA256: `05642da1e77e24273e83c99bab863a99aefb442846caccf038bb95a8f0a3a79a`
- ZIP bytes: `63,386,281`
- Runtime/export commit: `1c6591fb`

Keep `the-aftertimes.x86_64` and `the-aftertimes.pck` in the same extracted folder.

## Run the playtest

### Linux review zip

Download and extract the public Linux review zip, then run:

```bash
sha256sum the-aftertimes-realm1-linux-1c6591fb.zip
unzip the-aftertimes-realm1-linux-1c6591fb.zip
chmod +x the-aftertimes.x86_64
./the-aftertimes.x86_64
```

The hash should print `05642da1e77e24273e83c99bab863a99aefb442846caccf038bb95a8f0a3a79a`.

Public Windows/macOS/web/mobile packages are not part of this review packet; judge the Linux build above.

## Goal for a first run

1. Choose **Wake the Shelter**.
2. Pick any class.
3. Survive and scavenge on the surface long enough to find a bunker entrance.
4. Enter the bunker, build the required rooms, recruit Mira/Jonas/Archivist, and craft reactor parts.
5. Assemble and steady the **Geothermal Reactor**.
6. Use the unlocked bunker elevator and confirm the road-home payoff.
7. Save, quit to title, Continue, and confirm the win/reactor state survives load.

## External QA ship-gate rubric

This is the human pass/fail bar for the open Realm 1 completion gate. A test
does **not** count as a ship-gate pass if the player needed agent/dev help,
walkthrough notes, debug inventory, save editing, console commands, or a
preloaded late-game save.

For a **PASS**, one external tester must complete a fresh run on the target
build and report all of the following:

- Started from the title menu and chose a survivor without external help.
- Reached the bunker from normal surface play.
- Recruited Mira, Jonas, and the Archivist.
- Built at least seven rooms and crafted the required reactor parts.
- Completed the Geothermal Reactor / Realm 1 payoff.
- Opened Return Loop / Earth Remembers credits.
- Heard the post-credits crew finale lines.
- Saved, quit to title, used Continue, and verified the completion state
  persisted.
- Saw no crash, data loss, missing file, blocking runtime error, or dead-end
  progression.
- Reports only minor issues, or explicitly marks any major clarity/quality issue
  as non-blocking for a paid first-chapter candidate.

For a **FAIL**, record the exact blocking moment, visible objective/copy,
what the tester tried, and screenshots/video/logs if possible.

## Controls

### Title and class select

- Title menu: `W/S` or arrow keys move selection; `Enter` / `Space` activates; **Credits / Licenses** opens notices; `Esc` quits or closes credits.
- Class select: `Left` or `Right` chooses a survivor; `Enter` or `Space` wakes the Shelter.

### Shared gameplay defaults

| Action | Default input |
|---|---|
| Move | `W/A/S/D` |
| Jump / confirm where shown | `Space` |
| Attack | `J` or left mouse |
| Interact / use / enter | `E` or `Enter` |
| Run / dodge | `Shift` |
| Inventory bar | Always visible bottom-left; `I` closes crafting menu |
| Craft menu | `C`, then `↑/↓` and `Enter` |
| Pause | `Esc` or `P` |
| Minimap | Always visible top-right |
| Journal | `L` |
| Build mode | `B` |
| Dig / excavate | `X` in bunker; hold a direction to choose dig direction |
| Repair cave chamber | `E` in bunker when the selected cave chamber is damaged |
| Convert cave chamber | `B` in bunker when a selected ancient chamber is repaired/intact |

### Basic gamepad defaults

Gamepad is supported for the core Realm 1 loop, but controller remapping is not
part of this playtest.

| Action | Default gamepad input |
|---|---|
| Move / menu navigation | Left stick or D-pad |
| Jump / confirm in menus | A |
| Cancel / close menus | B |
| Attack | X |
| Interact / use / enter | Y |
| Run / dodge | Left shoulder |
| Build | Right shoulder |
| Craft menu | Right trigger, then A to craft |
| Dig / excavate | Left trigger |
| Cycle room plans | Left stick click |
| Move build cursor | Right stick left/right |
| Journal | Back |
| Return to surface | Right stick click |
| Pause | Start |

### Bunker-specific controls

The bunker HUD shows the full row:

`A/D Move · Shift Run · W/S Stairs · Space Jump · Tab Plan · N/M Cursor · B Build · X Dig · C Craft · Enter Craft · E/Enter Use/Repair/Reactor · L Journal · R Surface · Esc/P Pause`

If controls are rebound, runtime HUD, tutorial, crafting, and journal help
replace the rebindable gameplay keys. Enter/Esc remain explicit confirm/cancel
fallbacks.

### Rebinding, volume, and readability

Open pause with `Esc` or `P`.

- `W/S` or arrow keys move through rows.
- `Left/Right` adjusts volume or chooses the controls action.
- On the **Controls** row, press `Enter`, then press the replacement key.
- On the **Colorblind/readability** row, press `Enter` to toggle the safer palette.
- Settings persist to `user://settings.json`.

Rebindable actions are: move up/down/left/right, jump, attack, interact,
run/dodge, close crafting menu, journal, craft, build, dig/excavate, and pause.

## Save, load, and local data

- The title menu has **Wake the Shelter**, **Continue**, **Credits / Licenses**, and **Quit**.
- The in-game pause menu has **Continue**, **Save**, **Load**, and **Quit to Title**.
- Pause-menu Save writes the quick slot `autosave`.
- Save files are JSON at `user://saves/save_<slot>.json`; the common quick-save file is `user://saves/save_autosave.json`.
- Settings live at `user://settings.json`.

Typical Linux `user://` path is:

```text
~/.local/share/godot/app_userdata/The AfterTimes
```

If a tester cannot find the folder, search their machine for
`telemetry_aftertimes.jsonl` or `save_autosave.json` after one save/death/build.

## Telemetry

Telemetry is local-only JSONL. No network analytics are sent.

Public telemetry/redaction guide:
<https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_TELEMETRY_REVIEW_GUIDE.md>

File:

```text
user://telemetry_aftertimes.jsonl
```

Currently recorded events:

- `player_death`
- `room_built`
- `reactor_completed`

If comfortable, include the last few JSONL lines with feedback. Do not send
private machine paths if you do not want them shared.

## What to judge

Focus feedback on the parts that must be strong before Realm 1 can ship:

- First-run clarity: did you know what to do without agent help?
- Class choice: did the class card and start feel meaningful?
- Surface exploration: fog of war, lantern/darkness, night/day, storms, item readability, landmarks, bunker discovery.
- Combat and survival pressure: readable threats, fair deaths, useful attacks/run/dodge.
- Bunker/base quality: seamless multi-level layout, stairs/shafts, varied room shapes, non-boxy art, room purpose clarity.
- Progression: resource pacing, room build order, NPC recruitment, reactor-part crafting, reactor win, and the local elevator next-chapter payoff.
- Controls: default comfort, rebinding, pause menu, save/load trust.
- Accessibility/readability: font size, HUD colors, colorblind mode, storm/darkness readability.
- Art/animation: walking, running, jumping/hopping, attacks, build/dig/interact, NPC/enemy loops at gameplay scale. Report any weak loop as a quality issue; do not assume it is intentionally final.
- Stability: crashes, runtime errors, missing files, bad loads, audio failures, frame drops.

## What not to judge yet

These are intentionally not part of the current Realm 1 playtest verdict:

- Realms 2-6 content. They remain roadmap content after Realm 1 is proven.
- macOS, web, mobile, controller remapping, or platform certification.
- Cloud saves, multiplayer, or online telemetry.
- Final store page/capsule/trailer polish.
- Final paid-release art approval. Current Realm 1 art/animation is wired and playtestable, but still replaceable if final critique finds a weak visible loop.

## Known pre-QA caveats

- Realm 1 remains **not ship-ready** until external human new-player completion QA and final art/animation critique where required.
- Windows/macOS/web/mobile runtime proof is deferred; do not use this packet for non-Linux platform claims.
- Optional Agent Hub / LLM dialogue is not required; fallback dialogue keeps the game playable offline.
- This is a prerelease external-review package, not a public paid launch.

## Feedback format

Preferred: open the public **External QA playtest report** form: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=playtest_report.yml>.

If reporting elsewhere, include:

1. OS and hardware basics.
2. Artifact name and hash if available.
3. Class picked.
4. Whether you used outside help; if yes, where and why.
5. Time to completion or time spent before blocking.
6. How far you got: surface only, bunker entered, NPCs recruited, rooms built, reactor completed, credits/crew finale, save/load verified.
7. Biggest confusion point.
8. Most satisfying moment.
9. Any weak art/animation loop, with screenshot/video if possible.
10. Any crash/runtime error and exact steps to reproduce.
11. Optional: relevant `telemetry_aftertimes.jsonl` lines.
