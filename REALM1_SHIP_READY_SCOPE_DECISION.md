# Ship-Ready Scope Decision v1

> **Historical evidence only — superseded 2026-07-10.** The active stricter
> top-tier review is **NOT RELEASE-CERTIFIED**, with an accepted native-input
> matrix of **0/22**. See [CURRENT_TOP_TIER_REVIEW_STATUS.md](CURRENT_TOP_TIER_REVIEW_STATUS.md).

Date: 2026-07-07  
Scope: close the remaining store/legal/platform/publication gate without relying on human review.

## Verdict

Historical PASS for the former scoped public Linux package release. This verdict no longer represents the current release status.

This is not a Steam/itch paid-store publication approval. Steam, itch, GitHub Releases assets, platform account/app IDs, payout/tax setup, regional pricing, dedicated press/social channels, Windows runtime claims, macOS, web, and mobile are explicitly deferred from this ship-ready scope.

## Final scoped release claim

- Product: **The AfterTimes — Realm 1**.
- Distribution: public support repository + GitHub Pages support page.
- Platform claim: Linux x86_64 only.
- Package: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-b1e41bab.zip>.
- ZIP SHA256: `296aa58f7992a78486aee7e7ef39bedf266aefe968ce4f870d0442bc9b581621`; bytes `63,586,751`.
- Runtime/export commit: `b1e41bab` (`b1e41babead9c3ef061b9c4073587a844cf96ea4`).
- Support proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_REPO_DOWNLOAD_B1E41BAB.md>.
- Support ship-scope proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_SHIP_READY_SCOPE_DECISION.md>.
- Support tag: `realm1-linux-b1e41bab`.
- Issue #3 closure proof: main <https://github.com/elias-leslie/the-aftertimes/issues/3> and support <https://github.com/elias-leslie/the-aftertimes-support/issues/3> are closed completed for this scope as of 2026-07-07T19:18Z.

## Gate audit

| Gate | Decision | Evidence |
|---|---|---|
| Completion / full loop | PASS | `docs/PLAYTEST_REPORTS/2026-07-07-public-repo-download-b1e41bab-v1.md`; completion contact SHA `72686288b998621a2098d326d3541204cec9128b5444333a7c02dde4f12391ca`; completion log SHA `6718bab2007810bf4150a37b21320c2817726a7edf6120cbf08b14db4610d528`. |
| Visual / graphics / art | PASS | Runtime launch contact SHA `aaad370c9cbde3f9a27672eafa29eeaf44ff142026652359c2c712f138352ae5`; Agent Hub `game-art-critic` session `d1755855-4d0c-4c13-ae26-0a680deda0ea` PASS; visual polish proof in `docs/visual_proofs/2026-07-07-visual-release-polish-v1/`. |
| Audio / music / SFX | PASS | `scripts/measure_audio_quality.py` current metrics: 34 files, 399.99s, true-peak max -1.4 dBFS, 0 issues/0 warnings; Agent Hub `verifier` session `f0e43afa-60c4-46ce-a413-74fe7b6ed2c0` FINAL PASS. |
| Package integrity | PASS | Local ZIP SHA/inner `SHA256SUMS.txt` passed; extracted headless smoke PASS; public redownload byte/SHA matched; public inner hashes and extracted headless smoke passed. |
| Public publication path | PASS | Support repo and GitHub Pages expose package URL, run instructions, package proof, completion proof, art/audio packet, Credits/Licenses proof, SECURITY, LICENSE, NOTICE, and support issues. Browser/Page marker proof is recorded in the b1e41bab report. |
| Legal/license/privacy evidence for this scope | PASS | Public `LICENSE`, `NOTICE`, `SECURITY.md`, `REALM1_CREDITS_LICENSES_PROOF.md`, and telemetry guide document Apache-2.0 distribution, notices, no account system, no network analytics, and local-only JSONL telemetry. |
| Store/account/tax/pricing fields | DEFERRED | Paid Steam/itch/storefront sale is outside this scope. No tax IDs, payout data, app IDs, or private account details are needed for the repo-hosted Linux package. Reopen before any paid storefront sale. |
| Platform claims beyond Linux | DEFERRED | Windows artifact exists but runtime claim is deferred; macOS/web/mobile are out of scope. Public wording must claim Linux only until matching runtime proof exists. |
| Human review dependency | REMOVED | Issue #1 and #2 are closed by deterministic/runtime/A-Loom/Agent Hub proof; issue #3 close condition is concrete field decisions or deferrals, not unspecified human review. |

## Deferred paid-store checklist

Before a future Steam/itch/GitHub Releases asset launch, reopen a dedicated release-store gate for:

- platform account/app ID and release-owner setup;
- payout, tax, regional pricing, discounts, and currency handling;
- store-specific screenshots/capsule ordering/crop and trailer upload;
- final store page, tags, Early Access wording, and platform-specific claims;
- Windows/native platform runtime proof if claiming any non-Linux platform;
- credential-bound upload proof for the selected store or GitHub Release asset.

These are future publication tasks, not blockers for the current repo-hosted Linux ship scope.
