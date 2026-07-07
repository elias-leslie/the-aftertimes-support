# Realm 1 Agentic Release Quality Gates

Status: current agentic art/audio/release-quality gate evidence for `b1e41bab`.

This page supersedes older wording that treated paid launch as blocked on vague human review. Current completion gates use deterministic runtime proof, A-Loom/runtime asset handoffs, Agent Hub visual/audio reviewers, and concrete release-field decisions.

## Current verdicts

- Completion proof: `PASS` — current no-injection scripted completion reaches class select, surface survival, 3 NPCs, bunker, 7 rooms, reactor, elevator/win, save, title Continue, and reload.
- Audio/SFX: `PASS` — 34 runtime audio files, 399.99s total, true-peak max -1.4 dBFS, 0 metric issues; Agent Hub verifier reports `STATUS: verified`.
- Reactor hum: `PASS` — rebuilt from a 7s loop to a 30.040816s stereo MP3 loop at 128k, true peak -4.6 dBFS, with refreshed waveform proof.
- Visual/graphics: `PASS` — second-pass runtime/A-Loom proof and Agent Hub critics verify UI hierarchy/button weight, keybinding legibility, bunker detail parity, and radiation haze texture.
- Store/legal/platform: `PASS for scoped Linux repo-hosted publication` / `DEFERRED for paid storefronts` — package publication, public support route, legal/privacy/support docs, and Linux-only platform claim are complete; Steam/itch paid sale, platform account/app IDs, payout/tax/regional pricing, GitHub Release asset upload, dedicated press/social channels, Windows runtime claims, macOS, web, and mobile are deferred future release gates.


## Tracker status

- Completion QA tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/1> is closed as superseded by deterministic runtime proof.
- Visual/audio gate tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/2> is closed completed with final visual/audio `PASS`.
- Store/legal/platform tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/3> is closed for the scoped Linux public package; reopen only for paid storefronts, non-Linux platform claims, or credential-bound release uploads.

## Public proof links

- Ship-ready scope decision: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_SHIP_READY_SCOPE_DECISION.md>
- Current package proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_REPO_DOWNLOAD_B1E41BAB.md>
- Current completion proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_AUTOMATED_COMPLETION_PROOF.md>
- Current art/audio packet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_ART_AUDIO_REVIEW_PACKET.md>
- Visual release polish proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_VISUAL_RELEASE_POLISH_V1.md>
- Reactor hum waveform proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/reactor-hum-waveform-public-proof.png>
- Credits/Licenses proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_CREDITS_LICENSES_PROOF.md>

## Deferred future storefront gates

1. Paid Steam/itch or GitHub Releases asset publication needs platform accounts, app IDs, payout/tax/regional pricing, and credential-bound upload proof.
2. Non-Linux platform claims need native/fixed-runtime proof before publication.
3. Refresh the exported package/screenshots only if future runtime visuals change again.
