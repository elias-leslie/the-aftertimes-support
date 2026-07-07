# Realm 1 Public Repo-Hosted Review Package 35a52259

Status: **source-fresh public review package**, not a paid public launch.

This package is hosted in the support repository as a fallback while GitHub Release
asset publication for `35a52259` is pending. Use this ZIP for new external review.
The older GitHub Release asset `realm1-review-a5392e7c` remains available only as
superseded release-lineage evidence.

## Download

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-35a52259.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-35a52259.zip>
- ZIP filename: `the-aftertimes-realm1-linux-35a52259.zip`
- ZIP SHA256: `32b9dbdfcb1ccb77ac527e59bc6ee8f6aa6ff8bda6bb9a01ea4b2ad7bfbae6dd`
- ZIP bytes: `63,381,905`
- Runtime/export commit: `35a52259`

## Inner export identity

- Linux executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- Linux executable bytes: `73,433,400`
- Linux `.pck` SHA256: `bbf55141c3851fe943be43c503e8dc16158c8edbec3fe5e3948315d40754ec3f`
- Linux `.pck` bytes: `36,554,412`

## Source-local pre-publication proof

- Local package manifest: `docs/visual_proofs/2026-07-07-local-review-package-after-duplicate-room-plan-hud-copy-v1/build_manifest-35a52259.json`
- Local package smoke log SHA256: `037dd8b42ca7058b62b5555724cff76b748c651cb2252ee73dac52a938d0ecd2`
- Launch screenshot contact: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/launch-screenshots-v2-contact.png>
- Launch screenshot contact SHA256: `2cdd5ba696a55c05d62dafc2bb54b711222c4ef90fdcbc06f5f7c97968a8b1ab`
- Duplicate room-plan HUD runtime proof screenshot SHA256:
  `8808b521e169b5200593d83e7dedec0fb1215cdb409ffdfd0682f8b9bab5a883`

## Public verification

Public redownload verification is recorded in the game repo report
`docs/PLAYTEST_REPORTS/2026-07-07-public-repo-download-35a52259-v1.md` and proof
bundle `docs/visual_proofs/2026-07-07-public-repo-download-35a52259-v1/`.

- Public ZIP fetch: HTTP `200`, content type `application/zip`, downloaded bytes
  `63,381,905`, effective URL
  `https://raw.githubusercontent.com/elias-leslie/the-aftertimes-support/main/downloads/the-aftertimes-realm1-linux-35a52259.zip`.
- Public ZIP SHA256 matched
  `32b9dbdfcb1ccb77ac527e59bc6ee8f6aa6ff8bda6bb9a01ea4b2ad7bfbae6dd`.
- Extracted inner hashes matched the executable and `.pck` identities above.
- Extracted Linux build completed `./the-aftertimes.x86_64 --headless --quit-after 60`.
- Public support page fetch returned HTTP `200` and current `35a52259` markers.
- Browser check of <https://elias-leslie.github.io/the-aftertimes-support/#current-review-build>
  reported `errors=0`, `warnings=0`, `network=0`; screenshot SHA256
  `2baecd8b6702b7018c7f4836835621b333b0fa8e480475c68fc5e38383c5cd04`.
- Verification log SHAs: public download/smoke
  `cc8341c411d46597cac8b661366e2ef879afb5092106cc6f0cb286f564383143`,
  public support fetch
  `2772ca1610ee9238743384e47138c4887336fb3a483a673e8d6674e9a48551c6`,
  browser check
  `ffc643964c011d04b88a4c1430ec7d17d305d2f5f40cd4558fb5669359b1c031`.

## Run on Linux

```bash
sha256sum the-aftertimes-realm1-linux-35a52259.zip
unzip the-aftertimes-realm1-linux-35a52259.zip
chmod +x the-aftertimes.x86_64
./the-aftertimes.x86_64
```

The hash should print `32b9dbdfcb1ccb77ac527e59bc6ee8f6aa6ff8bda6bb9a01ea4b2ad7bfbae6dd`.
