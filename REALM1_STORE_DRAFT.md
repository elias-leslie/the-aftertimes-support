# The AfterTimes Realm 1 Store Draft

Status: **draft for external legal/store/business review; not approved for paid publication yet.**

This page mirrors the current non-secret launch/store copy from the game repo so reviewers can check store description, tags, Early Access wording, trailer outline, pricing rationale, and known blockers without private repo access. Do not treat this as a live store page approval.

Current review build: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-d3fc7d09>  
Public review status: <https://elias-leslie.github.io/the-aftertimes-support/#review-status>  
Legal/store review form: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=release_legal_store_review.yml>


## Product positioning

**Title:** The AfterTimes  
**Tagline:** Rebuild humanity. One realm at a time.  
**Genre line:** Single-player 2D survival-builder with top-down scavenging and side-view bunker building.  
**Current product promise:** Realm 1 is a complete first chapter: survive the irradiated surface, carve out a bunker, recruit specialists, build the Geothermal Reactor, open the Return Loop, and witness the Earth Remembers closure.

### Target player

Players who like:

- Survival pressure without multiplayer dependency.
- Base-building that feels like a lived-in home, not a rectangular room grid.
- Fog-of-war exploration, lantern-lit darkness, weather, storms, and ruins.
- Crafting/resource pressure with a clear chapter win condition.
- Story closure with survivors, saved colonies, and a post-credits epilogue.
- Gothic, mysterious, low-tech post-collapse 2D art.

## Steam short description draft

Plain text only; no time-based copy.

> Build humanity's first refuge in a dying wasteland. Scavenge a fog-shrouded surface, carve a multi-level bunker, recruit survivors, restore the Geothermal Reactor, and uncover Earth Remembers in the first chapter of a multi-realm survival-builder.

Character count: 247 including spaces.

## itch.io short description draft

> Scavenge an irradiated surface, carve a multi-level bunker, recruit survivors, and uncover Earth Remembers.

## Long store description draft

### Rebuild humanity from the dirt up.

The surface is poisoned. The storms are getting worse. Every trip above ground
is a wager against the radiation meter: push deeper into the ruins for one more
cache, one more tool, one more lead on a bunker entrance, then get below before
the world eats through your suit.

Underground, the pace changes. Your bunker is home: a side-view, multi-level
base of carved rock, patched machinery, stairs, shafts, storage, crafting,
water, defense, quarters, and a reactor site. Build it out, recruit specialists,
and turn scavenged junk into the parts needed to wake the old Geothermal Reactor.

Realm 1 is the first chapter of The AfterTimes. The reactor is not just a
checklist: it opens the Return Loop, lets the bunker hear what the saved
colonies became, and closes on the Earth Remembers ledger. This chapter reaches
a real ending while pointing toward later realms.

### Key features

- **Two connected views:** top-down surface exploration above, side-view bunker building below.
- **Radiation pressure:** surface runs are short at first; gear, planning, and bunker progress make them safer.
- **Fog, darkness, and weather:** explore with limited sight through fog of war, lantern light, night, rain, dust, wind, and radiation storms.
- **A bunker that should feel built, not stamped:** varied room sizes, stairs, shafts, shoring, supports, and seamless Gothic survival art.
- **Procedural cave/base finds:** empty caves, ancient homes, damaged rooms, repair opportunities, and rare buried finds shape each bunker path.
- **Six survivor classes:** choose a starting specialty and point-buy identity for the first surface run.
- **Recruit specialists:** find and bring Mira, Jonas, and the Archivist into the bunker to support the reactor push.
- **Craft the win condition:** gather, craft, build, and assemble the Geothermal Reactor to finish Realm 1.
- **A real chapter ending:** witness Earth Remembers credits, post-credits crew finale lines, and a saved-colony ledger that stays in the bunker after Continue.
- **Offline-first:** playable without online services; optional local telemetry exists only as JSONL for playtest review.

### Early-access honesty block

The AfterTimes should not be sold as the full six-realm saga yet. The first paid
candidate is Realm 1 only. Realms 2-6 are roadmap content and should be described
as planned direction, not promised launch content, until production starts under
a separate task.

## Tags

### Steam tag targets

Primary: `Survival`, `Base Building`, `Crafting`, `Exploration`, `Singleplayer`  
Secondary: `Post-apocalyptic`, `2D`, `Atmospheric`, `Procedural Generation`, `Resource Management`, `Story Rich`, `Dark`, `Pixel Graphics` / `2D Art` depending on final art taxonomy.

### itch.io tag targets

`survival`, `base-building`, `crafting`, `exploration`, `post-apocalyptic`,
`singleplayer`, `2d`, `procedural`, `gothic`, `atmospheric`

itch.io recommends up to 10 tags on the creator getting-started page.

## Trailer outline

Target length: 55-70 seconds. Minimum public trailer requirement before Steam
Early Access: gameplay footage, not just mood art.

1. **0-4s — Hook:** black screen, storm audio, lantern circle reveals ruins. Title fades in.
2. **4-12s — Surface risk:** fast cuts of fog-of-war exploration, resource grabs, radiation meter falling.
3. **12-20s — Threat:** wildlife/raider/anomaly attack; player runs, dodges, counters.
4. **20-31s — Descent:** bunker entrance, switch to side-view, first rooms and stairs appear.
5. **31-42s — Build home:** storage, workshop, generator, water, quarters, NPCs moving/talking.
6. **42-52s — Cave mystery:** empty cave/ancient dwelling/damaged room/rare find montage.
7. **52-63s — Reactor win:** craft parts, assemble reactor, blue core lights, elevator unlocks.
8. **63-70s — CTA:** The AfterTimes logo; “Realm 1: The first chapter” if platform rules allow in trailer end card. Avoid capsule-only text misuse.

## Release notes draft — Realm 1 playtest / v0.1.0

- Realm 1 playable loop: class select, surface run, bunker entry, base building, NPC recruitment, reactor build, elevator/win state, Return Loop epilogue, Earth Remembers credits, and title Continue after the ending.
- Six player classes with class cards and starting modifiers.
- Surface exploration with fog of war, lantern/darkness, day/night, fog, wind, dust, rain, and radiation storms.
- Side-view bunker with multi-level rooms, stairs, shafts, generator/storage/workshop/water/quarters/med/defense/reactor spaces.
- Cave/base variants: empty excavation, ancient intact/damaged sites, repair hooks, rare finds, and irregular room conversions.
- NPC recruitment and final crew epilogues: Mira, Jonas, Archivist.
- Crafting and resource economy for ammo, room builds, and reactor parts.
- Player-facing save/load, pause menu, key rebinding, master volume, and colorblind/readability toggle.
- Post-credits crew finale autosaves, load toasts, journal closure, and title Credits/Licenses colony roll.
- Local-only JSONL telemetry for player death, room build, and reactor completion events.
- Linux export smoke passed on this system. Windows artifact exists, but Windows runtime work is deferred for now by user direction; current Wine 9.0 failures remain future platform QA evidence.

## Pricing rationale draft

Recommended first paid candidate: **$9.99 USD Realm 1 early-access / first-chapter price**, only after QA blockers pass.

Rationale:

- The product is a complete first chapter with a real ending and epilogue, not the full six-realm saga.
- Lower early-access price rewards early supporters while Realm 1 gets human QA, final art/audio critique, and platform hardening.
- Do not discount immediately after a future price increase; Steam Early Access docs warn that discounts are blocked for 30 days after increases.
- Future price increases should happen only after material new content or a full 1.0 transition, and must be communicated clearly in the Early Access Q&A.
- itch.io can mirror the same base price or use “pay what you want” above the base only if support burden stays manageable.

Do not publish pricing until current competitive checks, taxes/region settings, platform fees, and business/legal setup are reviewed.

## Steam Early Access Q&A draft

Use only if choosing Steam Early Access rather than a closed playtest/Coming Soon page.

**Why Early Access?**  
Realm 1 is playable, but The AfterTimes benefits from real players testing the surface/bunker loop, pacing, readability, cave/base generation, combat pressure, class value, and save/load trust before the full saga expands.

**Approximately how long?**  
Do not publish a fixed date yet. Internal target is to stabilize Realm 1 first, then decide the Deep Cold production contract after playtest evidence. Use a broad window only after external QA confirms the current chapter is reliable.

**How will the full version differ?**  
The long-term design includes additional realms, deeper biome-specific building, more NPC/story content, richer art/audio polish, and broader platform QA. Do not promise all roadmap realms as part of the current paid chapter until production is funded and scheduled.

**What is the current state?**  
Realm 1 contains the first-chapter loop: class select, top-down surface survival/exploration, side-view bunker building, NPC recruitment, crafting, cave/base variants, Geothermal Reactor win, Return Loop/Earth Remembers ending, post-credits crew epilogue, save/load, key rebinding, accessibility/readability mode, local telemetry, Linux export proof, and Windows export artifact. Remaining blockers for the current local-system playtest candidate are external human new-player QA and final art/animation/audio critique where required. Windows runtime execution is deferred for now; this host's current Wine 9.0 failures remain future platform QA evidence.

**Will price change?**  
The current recommendation is a lower first-chapter early-access price, with possible increases only after material new content or a full 1.0 transition. Communicate any planned increase before it happens.

**How will the community be involved?**  
Use structured playtest feedback, bug reports, optional local telemetry snippets, screenshot/video reports, and update posts focused on onboarding, pacing, surface readability, bunker/base quality, combat fairness, art/animation quality, and save/load reliability.

## Press kit / factsheet draft

| Field | Draft |
|---|---|
| Title | The AfterTimes |
| Developer / publisher | SummitFlow Solutions LLC |
| Engine | Godot 4.7-stable |
| Platforms | Current local-system playtest: Linux/current host. Windows desktop artifact exists but runtime QA is deferred; macOS/web/mobile deferred. |
| Genre | Single-player survival-builder |
| Views | Top-down surface exploration; side-view underground base |
| Release model | Realm 1 first-chapter early-access candidate; not publish-ready until blockers pass |
| Website / social | Public project/support page: <https://elias-leslie.github.io/the-aftertimes-support/>; page also includes current Linux run instructions, the public playtest guide link, current screenshot contact sheet, capsule/key-art proof, public legal/security links, and current review-gate status. No separate social profile is approved; omit social links unless supplied later. |
| Press contact | Public support/review issues: <https://github.com/elias-leslie/the-aftertimes-support/issues>. No dedicated press inbox is approved; do not publish an invented email. |
| One-line pitch | Rebuild humanity in a dying wasteland by scavenging the surface, carving a bunker, and uncovering the Earth Remembers ledger. |

### Press short copy

The AfterTimes is a single-player survival-builder about rebuilding humanity one
realm at a time. In Realm 1, players scavenge an irradiated top-down wasteland,
retreat into a side-view bunker, recruit survivors, craft reactor parts, open
the Return Loop, and uncover the Earth Remembers ledger before the storms make
the surface unlivable.

## Business / release-field readiness packet

These fields are release blockers, not copywriting tasks. Do not guess values or
publish invented or unapproved links.

Latest repo evidence refresh: `docs/PLAYTEST_REPORTS/2026-07-03-public-review-status-v1.md`; public review-status proof `docs/visual_proofs/2026-07-03-public-review-status-v1/support-pages-html.html`; prior legal/security refresh `docs/PLAYTEST_REPORTS/2026-07-03-public-legal-security-docs-v1.md`; public legal/security docs proof `docs/visual_proofs/2026-07-03-public-legal-security-docs-v1/SECURITY.md`; public capsule/key-art proof `docs/visual_proofs/2026-07-03-public-capsule-key-art-v1/steam-capsule-family-v1-proof.png`; public screenshot contact proof `docs/visual_proofs/2026-07-03-public-screenshot-contact-v1/launch-screenshots-v2-contact.png`; public playtest guide proof `docs/visual_proofs/2026-07-03-public-playtest-guide-v1/REALM1_PLAYTEST_GUIDE.md`; public review run-instructions proof `docs/visual_proofs/2026-07-03-public-review-run-instructions-v1/support-pages-html.html`; public review intake proof `docs/visual_proofs/2026-07-03-public-review-intake-templates-v1/support-pages-html.html`; public review release proof `docs/visual_proofs/2026-07-03-public-review-release-v1/support-release-page-fetch.json`; public support privacy/telemetry proof `docs/visual_proofs/2026-07-03-public-support-privacy-note-v1/pages-fetch.json`; browser proof `docs/visual_proofs/2026-07-03-public-support-privacy-note-v1/support-privacy-note-browser.png`; prior support route proof `docs/visual_proofs/2026-07-03-public-support-route-v1/support-pages-web-fetch.json`. Prior business-field search proof: `docs/visual_proofs/2026-07-03-release-business-field-freshness-v1/business-field-search.txt` SHA `690d4136d5200df9bca2d8eea43e50836ef4a4fe6b78f8362408cfb83e2ec631`.

| Field | Current repo evidence | Required owner action before publication |
|---|---|---|
| Public website / social links | Public project/support URL exists: <https://elias-leslie.github.io/the-aftertimes-support/> and now includes current Linux run instructions, a public playtest guide link, the current screenshot contact sheet, capsule/key-art proof, public legal/security links, and current review-gate status at `#review-status`. No separate social profile is approved. | Use the support URL as the public project/support link if the platform accepts GitHub-hosted pages; otherwise provide a platform-specific website/social URL or approve omitting social links. |
| Public press / support contact | Public support/review issues exist: <https://github.com/elias-leslie/the-aftertimes-support/issues>. No dedicated press inbox is approved. | Use the public issue route for support/review contact if acceptable; otherwise provide a dedicated public inbox. |
| Privacy / telemetry wording | Public support repo now has public `SECURITY.md`, `LICENSE`, and `NOTICE`; public support page states local-only JSONL playtest telemetry/no network analytics and links the public docs. | External legal/store reviewer must still approve the wording before paid publication. |
| Store platform account | No Steam/itch account ids, app ids, payout setup, tax setup, or release owner fields are present in repo evidence. | Complete platform account, payout, tax, and app-id setup outside the repo, then record non-secret ids/status here. |
| Regional pricing | Draft base-price rationale exists at `$9.99 USD`; regional/tax/platform-fee review is not complete. | Approve base price, regional pricing policy, discounts, taxes, and currency handling. |
| Paid-release legal review | LICENSE, NOTICE, SECURITY, and credits panel exist; public support repo now mirrors LICENSE/NOTICE/SECURITY for reviewers. Final external paid-release legal/store review is still open. Intake template: `.github/ISSUE_TEMPLATE/release_legal_store_review.yml`. | Approve final store copy, license notices, privacy/telemetry wording, and third-party acknowledgements for sale. |
| Platform claims | Linux export smoke is proven; Windows export artifact exists but runtime execution is deferred; macOS/web/mobile are deferred. | Publish only platform claims with current runtime proof, or run the missing platform QA first. |

## Publication blockers

- External human full new-player completion QA: open in GitHub issue #1: <https://github.com/elias-leslie/the-aftertimes/issues/1>; public intake form: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=playtest_report.yml>.
- Final external art/animation/audio critique where required for paid release: open in GitHub issue #2: <https://github.com/elias-leslie/the-aftertimes/issues/2>; public intake form: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=art_animation_audio_review.yml>; source template `.github/ISSUE_TEMPLATE/art_animation_audio_review.yml`.
- Windows runtime execution on native Windows or a fixed Wine setup: deferred for now by user direction; keep current Wine 9.0 failures as future platform QA evidence.
- Final clean exported-build screenshots for NPC, combat, and reactor/elevator slots: closed for current internal evidence with native 1920×1080 capture and local visual inspection; external paid-release screenshot/art review remains a separate open blocker.
- Final capsule/key art generation and internal A-Loom approval: closed for the current Steam/itch/library family; external paid-release review/store decisions remain separate blockers.
- Store/legal/business fields: public support/project route now exists, but social links, dedicated press inbox, tax/regional pricing, platform account setup, final paid-release legal/store review via public intake form <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=release_legal_store_review.yml> / source template `.github/ISSUE_TEMPLATE/release_legal_store_review.yml`, and platform claims beyond current Linux proof remain open in GitHub issue #3: <https://github.com/elias-leslie/the-aftertimes/issues/3>.
