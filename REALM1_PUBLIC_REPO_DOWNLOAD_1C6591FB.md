# Realm 1 Public Repo-Hosted Review Package 1c6591fb

Status: current source-fresh public Linux review package. Paid launch remains blocked until external QA, art/audio, and legal/store/business issue verdicts pass or accepted deferrals are recorded.

This page proves the current source/export commit is available as a repo-hosted ZIP while formal GitHub Release asset publication is still blocked by credentials/tooling. Use this ZIP for new external review. The prior repo-hosted `682a0eb2` and `35a52259` packages and the GitHub Release asset `realm1-review-a5392e7c` remain superseded lineage only.

## Package identity

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-1c6591fb.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-1c6591fb.zip>
- ZIP filename: `the-aftertimes-realm1-linux-1c6591fb.zip`
- ZIP SHA256: `05642da1e77e24273e83c99bab863a99aefb442846caccf038bb95a8f0a3a79a`
- ZIP bytes: `63,386,281`
- Runtime/export commit: `1c6591fb`
- Linux executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- Linux `.pck` SHA256: `88ec801ccde394fba436c8d1bc8a97bf115b9464538eef1079aa8522535c9b17`
- Inner `build_manifest.json` SHA256: `1a6caae6369f7891865176fb83c038cbe81dd33b30bd3ed322ad11e08920ced3`
- Inner `SHA256SUMS.txt` SHA256: `c5f948b761fcb9ced5d38a5fcec8d9930ca3afedf1010b9b0b4f5e4fabbff1f3`

## Current 1c6591fb public proof refresh

- Automated no-injection completion proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_AUTOMATED_COMPLETION_PROOF.md>
- Completion contact sheet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/realm1-automated-completion-contact.png>
- Completion contact sheet SHA256: `a029d94df02890d40dec12a99d79aff78f15d3e86f32681392bf75fac771ed5d`
- Public package Credits / Licenses smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_CREDITS_LICENSES_PROOF.md>
- Credits / Licenses screenshot SHA256: `7f5deac1f824daa4f2df95ae46f8be7167460a159f836e285019b074ac2767c4`

## Export and launch screenshot proof

- Launch screenshot contact: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/launch-screenshots-v2-contact-1c6591fb.png>
- Launch screenshot contact SHA256: `d1de726b9f2dee02898e342801c21f213ad1dc2d381035390c0a64d1bd03b9ec`
- Local export/capture rerun log SHA256: `99eb2ce2d27439982a91e26805f2d164b1d028adfac276a555b4a98d77070d23`
- Local package smoke log SHA256: `e7105b8535c232c57f0e2221947fe1931940ffbe0f2e2f5f143d5a7635f36193`

Visual inspection result: the nine-panel contact sheet is readable; no blank/corrupt panel or runtime error overlay was observed.

## Local package verification

The package was assembled from the current Linux export and extracted locally.

- `sha256sum -c SHA256SUMS.txt` passed for the executable, `.pck`, build manifest, playtest guide, build doc, and README.
- The extracted executable kept mode `-rwxr-xr-x`.
- `./the-aftertimes.x86_64 --headless --quit-after 60` completed and printed `public_repo_download_smoke=PASS`.

## Public redownload verification

Public raw/download verification after support commit `5f7f4d5`:

- Public ZIP fetch returned HTTP `200`, content type `application/zip`, bytes `63,386,281`, and raw.githubusercontent effective URL.
- Downloaded ZIP SHA256 matched `05642da1e77e24273e83c99bab863a99aefb442846caccf038bb95a8f0a3a79a`.
- Extracted `sha256sum -c SHA256SUMS.txt` passed for executable, `.pck`, build manifest, playtest guide, build doc, and README.
- Extracted `./the-aftertimes.x86_64 --headless --quit-after 60` completed with `public_redownload_smoke=PASS`.
- Public README, proof doc, and Pages fetches returned current `1c6591fb` package markers.
- Browser check of the public support page reported `errors=0`, `warnings=0`, `network=0`, `command_warnings=0`.

Source-repo proof hashes: public download smoke log `c6165eb78acb101788a3fde16c2d91c34f9a6ec0447837ecb149f07bc20d25b6`; public support fetch log `d0b1668bc45f77c112c7b54a4848bad25090b1d73a6d37e4e21497e082ed55cb`; browser check log `f14a45d64816773d452e648b2894ee2a993ee1f9877609456f999aa97deff2c7`; browser screenshot `a8dc98ce7d6c9f66a451e1dd2368eb71bea129c85ea1d7a6a2c150e074ee541b`.

## Run instructions

```bash
sha256sum the-aftertimes-realm1-linux-1c6591fb.zip
unzip the-aftertimes-realm1-linux-1c6591fb.zip
chmod +x the-aftertimes.x86_64
./the-aftertimes.x86_64
```

The hash should print `05642da1e77e24273e83c99bab863a99aefb442846caccf038bb95a8f0a3a79a`.

## Remaining blockers

This package refresh does not close the external ship gates. External QA (#1), art/animation/audio (#2), and legal/store/business (#3) remain open until the public tracker issues record PASS or accepted MIXED/deferral decisions.
