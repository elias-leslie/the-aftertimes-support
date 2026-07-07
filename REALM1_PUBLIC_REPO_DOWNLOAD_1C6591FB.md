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

Public redownload verification is recorded in the source-repo proof report for this package. If viewing this file before the second verification commit lands, compare the ZIP SHA above to the public raw download after GitHub updates Pages/raw cache.

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
