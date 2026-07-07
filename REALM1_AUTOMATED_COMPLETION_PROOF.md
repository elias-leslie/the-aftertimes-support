# Realm 1 Public Automated Completion Proof

Status: current deterministic no-injection completion proof for the `1c6591fb` source/package line. It is the active completion QA evidence gate unless concrete runtime failures are found.

Use this as current proof that the `1c6591fb` review package has a proven complete path under fixed-seed scripted input. Public playtest feedback is still welcome, but paid launch is not blocked on vague human review.

## Build under review

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-1c6591fb.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-1c6591fb.zip>
- Zip SHA256: `05642da1e77e24273e83c99bab863a99aefb442846caccf038bb95a8f0a3a79a`
- ZIP bytes: `63,386,281`
- Runtime/export commit: `1c6591fb`
- Linux executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- Godot pack SHA256: `88ec801ccde394fba436c8d1bc8a97bf115b9464538eef1079aa8522535c9b17`
- Superseded lineage: prior repo-hosted `682a0eb2`/`35a52259` packages and GitHub Release asset <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Scope: prerelease external-review package, not a public paid launch.

## What the scripted proof covers

The current `1c6591fb` no-injection proof starts from title/class select, uses normal UI/input, survives the surface for two minutes, gathers generated resources through Interact, recruits Mira/Jonas/the Archivist, enters the bunker through player interaction, builds seven rooms, crafts reactor parts through the C overlay, powers the generator, repairs/assembles the Reactor Site, opens the elevator payoff, saves, quits to title, uses Continue, and reloads with `reactor_complete=true`.

It does **not** use debug inventory, save editing, console commands, or a preloaded late-game save. It uses a fixed proof seed and scripted input, so it is an agentic/deterministic completion gate; public unaided playtest feedback remains welcome but is not a human-review blocker.

## Public artifact

- Completion contact sheet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/realm1-automated-completion-contact.png>  
  SHA256 `a029d94df02890d40dec12a99d79aff78f15d3e86f32681392bf75fac771ed5d`

## Key milestones verified

- Title Wake the Shelter and class select Begin.
- Two-minute surface survival: radiation dropped to `119.5`, health stayed `1.00`.
- `53` generated resource nodes gathered through Interact input.
- Recruited `mira`, `jonas`, and `the_archivist`.
- Entered bunker through player interaction.
- Built storage, water filter, quarters, med bay, generator, defense post, and reactor site.
- Crafted reactor core, casing, and control through the crafting overlay.
- Reactor status reached `complete=true`, `elevator_unlocked=true`.
- Elevator payoff displayed: `Elevator doors open toward The Deep Cold. The road home begins.`
- Save/quit/title Continue reloaded with `reactor_complete=true`.

## Public QA feedback form

Submit optional public QA feedback here:

<https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=playtest_report.yml>

Paid launch is no longer blocked by issue #1 or vague human QA. It remains blocked by the current concrete gates: visual/graphics `PASS_WITH_FIXES`, store/legal/platform fields, and credential-bound publication proof.
