# Realm 1 Public Repo-Hosted Review Package b1e41bab

> **Historical archive — not the current review build.** The active stricter
> top-tier review is **NOT RELEASE-CERTIFIED / 0 of 22**. See
> [CURRENT_TOP_TIER_REVIEW_STATUS.md](CURRENT_TOP_TIER_REVIEW_STATUS.md).

Status: historical source-fresh public Linux archive and former narrow-scope proof. Its old PASS claims do not represent current release status.

This page proves the current source/export commit is available as a public repo-hosted ZIP. The scoped ship-ready decision is recorded in <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_SHIP_READY_SCOPE_DECISION.md>. Paid Steam/itch storefront sale, GitHub Release asset upload, platform account/app IDs, payout/tax/regional pricing, dedicated press/social channels, Windows runtime claims, macOS, web, and mobile are deferred future release gates. The prior repo-hosted `1c6591fb`, `682a0eb2`, and `35a52259` packages and the GitHub Release asset `realm1-review-a5392e7c` remain superseded lineage only.

## Package identity

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-b1e41bab.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-b1e41bab.zip>
- ZIP filename: `the-aftertimes-realm1-linux-b1e41bab.zip`
- ZIP SHA256: `296aa58f7992a78486aee7e7ef39bedf266aefe968ce4f870d0442bc9b581621`
- ZIP bytes: `63,586,751`
- Runtime/export commit: `b1e41bab`
- Full source commit: `b1e41babead9c3ef061b9c4073587a844cf96ea4`
- Linux executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- Linux `.pck` SHA256: `c2d00a6f492598b8519caf575610b354a27a2ff2c5833804960b31687564d6a6`
- Linux `.pck` bytes: `36,874,284`
- Inner `build_manifest.json` SHA256: `5f5344b2dca8929733213455b34b1d91a6d4f5dd01624738971504bb5df31c30`
- Inner `SHA256SUMS.txt` SHA256: `1ebc741892c49186f4afb16c9a6123596912dfb5e26690fbf11a54425ede00b3`

## Historical b1e41bab completion proof

- Automated no-injection completion proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_AUTOMATED_COMPLETION_PROOF.md>
- Completion contact sheet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/realm1-automated-completion-contact.png>
- Completion contact sheet SHA256: `72686288b998621a2098d326d3541204cec9128b5444333a7c02dde4f12391ca`
- Completion proof log SHA256: `6718bab2007810bf4150a37b21320c2817726a7edf6120cbf08b14db4610d528`
- Completion marker scan SHA256: `ce1f25e1227e088fb820e17321e7adee8e1935842977b8e3b05e1cc28fd40518`

The historical b1e41bab scripted proof starts at the title menu, uses normal UI/input, survives a two-minute surface run, gathers 53 resources through Interact, recruits Mira/Jonas/the Archivist, enters the bunker through player interaction, builds seven rooms, crafts reactor parts, powers/repairs/assembles the Geothermal Reactor, opens the elevator payoff, saves, quits to title, uses Continue, and reloads with `reactor_complete=true`.

## Export and launch screenshot proof

- Launch screenshot contact: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/launch-screenshots-v2-contact-b1e41bab.png>
- Launch screenshot contact SHA256: `aaad370c9cbde3f9a27672eafa29eeaf44ff142026652359c2c712f138352ae5`
- Visual release polish proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_VISUAL_RELEASE_POLISH_V1.md>
- Current package Agent Hub visual review: `game-art-critic` session `d1755855-4d0c-4c13-ae26-0a680deda0ea` returned `PASS` with no blockers.

Visual inspection result: the nine-panel contact sheet is readable; no blank/corrupt panel, debug overlay, or placeholder blocker was observed. Minor recommendations are polish-only: call-to-action emphasis, tiny icon sharpness, and lighting-style consistency.

## Audio/SFX proof

- Audio/SFX metrics: 34 files, 399.99s total, 18 SFX / 7 ambience / 8 music / 1 loop, true-peak max -1.4 dBFS, 0 issues, 0 warnings.
- Current package Agent Hub audio verifier: `verifier` session `f0e43afa-60c4-46ce-a413-74fe7b6ed2c0` returned `FINAL: PASS` and verified 7/7 atomic claims.
- Public art/audio packet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_ART_AUDIO_REVIEW_PACKET.md>

## Local package verification

The package was assembled from the current Linux export and extracted locally.

- `sha256sum -c SHA256SUMS.txt` passed for the executable, `.pck`, build manifest, playtest guide, build doc, and README.
- Extracted `./the-aftertimes.x86_64 --headless --quit-after 60` completed successfully.
- Local package smoke log SHA256: `037dd8b42ca7058b62b5555724cff76b748c651cb2252ee73dac52a938d0ecd2`
- Inner hash-check log SHA256: `6fb747622a1c66d8b2a49dc982b6d24ebef175b655143ecffe8a36a541c22c72`

## Public redownload verification

Public verification after support commit `97cd4fd`:

- Public ZIP fetch returned bytes `63,586,751` and SHA256 `296aa58f7992a78486aee7e7ef39bedf266aefe968ce4f870d0442bc9b581621`.
- Extracted `sha256sum -c SHA256SUMS.txt` passed for the executable, `.pck`, build manifest, playtest guide, build doc, and README.
- Extracted `./the-aftertimes.x86_64 --headless --quit-after 60` completed successfully.
- Public raw README, proof doc, and Pages HTML contained the current `b1e41bab` package markers, ZIP SHA, launch contact SHA, and completion contact SHA.
- Browser verification: `st browser check` first returned `errors=0`, `warnings=0`, `network=0`; the later screenshot subcommand had local browser infra trouble, so a fallback headless Chrome screenshot/DOM capture verified the GitHub Pages UI rendered the `b1e41bab` current-review-build section with the current ZIP SHA.

Source proof hashes: public download summary `03ea31bdc61bdc14e572bc1ce8bd2fe0b62fcf9fda1d2db85737269ff261a3d3`; curl headers `9f720c4115b6445d3d51bc89adb2857555b93d2b512069b8f2e02265f6cf5bd8`; public inner hash-check log `6fb747622a1c66d8b2a49dc982b6d24ebef175b655143ecffe8a36a541c22c72`; public headless smoke log `037dd8b42ca7058b62b5555724cff76b748c651cb2252ee73dac52a938d0ecd2`; public marker fetch log `24ecf238c4d61957d06bd0025925e75d25ff469906a917ddcc578d09a0c47d41`; support-page screenshot `1fb7e77e2688fdf78d5e2f74fa78ac886f528f4bd2fb5c57caf259f431bc1c54`; support-page DOM dump `c56664d60ec83370cc27b8051a9d9aa459f7626d87e786a1b6210ce72aed7368`.

## Run instructions

```bash
sha256sum the-aftertimes-realm1-linux-b1e41bab.zip
unzip the-aftertimes-realm1-linux-b1e41bab.zip
chmod +x the-aftertimes.x86_64
./the-aftertimes.x86_64
```

The hash should print `296aa58f7992a78486aee7e7ef39bedf266aefe968ce4f870d0442bc9b581621`.

## Ship-ready scope decision

This package closes the scoped public Linux ship gate. Completion QA is `PASS`, visual/graphics is `PASS`, audio/SFX is `PASS`, package integrity/public redownload is `PASS`, and the support-page publication path is `PASS`. Store/legal/business/platform work that requires paid storefront accounts, app IDs, payout/tax/regional pricing, GitHub Release asset upload, dedicated press/social channels, or non-Linux platform claims is explicitly `DEFERRED` to future release gates. No gate depends on vague human review.
