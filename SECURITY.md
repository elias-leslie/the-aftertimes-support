# Security Policy

## Reporting a Vulnerability

Do not open a public GitHub issue for a suspected security problem, secret,
private account detail, tax/payment detail, unreleased credential, or unredacted
local log/path.

Use GitHub private vulnerability reporting for the support repository when it is
available:

<https://github.com/elias-leslie/the-aftertimes-support/security/advisories/new>

If that route is unavailable, open a public support issue that asks for a
private reporting channel and does not include sensitive details.

Include privately:

- affected component, scene, or game system
- reproduction steps or proof of concept
- expected impact
- any known workaround or mitigation

## Supported Versions

| Version | Supported |
|---------|-----------|
| current public review package `realm1-review-d3fc7d09` | Yes |
| older snapshots | No |

## Response Expectations

Security reports are handled on a best-effort basis. No formal SLA is offered.

## What This Project Does and Does Not Collect

The AfterTimes is a single-player game. The public Realm 1 review build has no
network telemetry, no analytics service, no account system, and no online
check-in.

The review build may write local-only JSONL playtest events under `user://` for
player death, room build, and reactor completion review. Those files stay on the
player's machine unless the tester chooses to share them.

Do not post unredacted local logs, local paths, private machine information,
secrets, tax/payment data, or account data in public issues.
