# Realm 1 Public Automated Completion Proof

Status: previous scripted no-injection completion proof for the `682a0eb2` source/package line, retained as supplemental lineage for the current `1c6591fb` package. It does **not** replace external unaided human QA.

Use this as reviewer context that the previous `682a0eb2` build line had a proven complete path; run the current `1c6591fb` public build yourself for the external QA verdict.

## Build under review

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- Zip SHA256: `432d450275e7e42f7b000c8a9e4b7d488c8bf72e273d4638f89d395144f2b719`
- ZIP bytes: `63,382,521`
- Runtime/export commit: `682a0eb2`
- Linux executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- Godot pack SHA256: `0b1f2e59564ffeb6b4055e0ae6e56e11b3df6b2d365f8260a885260add24c671`
- Superseded lineage: prior repo-hosted `35a52259` package and GitHub Release asset <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Scope: prerelease external-review package, not a public paid launch.

## What the scripted proof covers

The previous 682a0eb2 no-injection proof starts from title/class select, uses normal UI/input, survives the surface for two minutes, gathers generated resources through Interact, recruits Mira/Jonas/the Archivist, enters the bunker through player interaction, builds seven rooms, crafts reactor parts through the C overlay, powers the generator, repairs/assembles the Reactor Site, opens the elevator payoff, saves, quits to title, uses Continue, and reloads with `reactor_complete=true`.

It does **not** use debug inventory, save editing, console commands, or a preloaded late-game save. It does use a fixed proof seed and scripted input, so a fresh unaided human playtest is still required for ship approval.

## Public artifact

- Completion contact sheet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/realm1-automated-completion-contact.png>  
  SHA256 `f0ced4893ea828de1d9f5567dfee06574bf3b7be875e2ebc40261f06085417b2`

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

## External QA form

Submit the required unaided human QA verdict here:

<https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=playtest_report.yml>

Paid launch remains blocked until issue #1 records PASS or an accepted MIXED/deferral decision.
