# Realm 1 Public Automated Completion Proof

Status: public scripted no-injection completion proof for the current Linux review build. It does **not** replace external unaided human QA.

Use this as reviewer context that the current build has a proven complete path, then run the public build yourself for the external QA verdict.

## Build under review

- Public review release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-d3fc7d09>
- Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-d3fc7d09/the-aftertimes-realm1-linux-d3fc7d09.zip>
- Zip SHA256: `5bfc0816d402dd94bfe0db16a36d283a55b63328581cc8a29f3b94245eb425fa`
- Runtime/export commit: `d3fc7d09`
- Scope: prerelease external-review package, not a public paid launch.

## What the scripted proof covers

The current no-injection proof starts from title/class select, uses normal UI/input, survives the surface for two minutes, gathers generated resources through Interact, recruits Mira/Jonas/the Archivist, enters the bunker through player interaction, builds seven rooms, crafts reactor parts through the C overlay, powers the generator, repairs/assembles the Reactor Site, opens the elevator payoff, saves, quits to title, uses Continue, and reloads with `reactor_complete=true`.

It does **not** use debug inventory, save editing, console commands, or a preloaded late-game save. It does use a fixed proof seed and scripted input, so a fresh unaided human playtest is still required for ship approval.

## Public artifact

- Completion contact sheet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/realm1-automated-completion-contact.png>  
  SHA256 `cea5cd6d022d2e4267717a4b7dac5448821425fe044bb8de9551d2ef7223a57f`

## Key milestones verified

- Title New Game and class select Begin.
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
