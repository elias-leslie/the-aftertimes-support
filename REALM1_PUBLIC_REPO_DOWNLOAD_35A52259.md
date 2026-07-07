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

## Source-local pre-publication proof summary

The support repo exposes the non-secret artifacts reviewers need publicly; deeper
source-local manifests and proof logs remain in the game repository. Publicly
visible pre-publication evidence:

- Launch screenshot contact: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/launch-screenshots-v2-contact.png>
- Launch screenshot contact SHA256: `2cdd5ba696a55c05d62dafc2bb54b711222c4ef90fdcbc06f5f7c97968a8b1ab`
- Duplicate room-plan HUD runtime proof screenshot SHA256:
  `8808b521e169b5200593d83e7dedec0fb1215cdb409ffdfd0682f8b9bab5a883`

## Public verification

Public redownload verification is summarized here so external reviewers do not
need private/source-repo access.

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


## Public runtime basic-smoke verification

A source-fresh basic UI/gameplay smoke is available publicly through the support
proof pages and screenshots below.

- Public title UI smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_UI_SMOKE.md>
  screenshot SHA256 `01f6c793a1c28810f8b7c2abcb58bcec4a2b55681ee9403cd06678a0924d552e`.
- Public class-select smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_CLASS_SELECT_SMOKE.md>
  screenshot SHA256 `1d3a7234972d0586a1b2f188b2e80bbacdc666fb4e6816a22bba311b2dbd6e94`.
- Public surface gameplay-entry smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_GAMEPLAY_ENTRY_SMOKE.md>
  screenshot SHA256 `5c0bfa073f9919792e1085f001a725b71219c457484a00985396d9ccde3b8bd2`.
- Public first-Storage build smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_FIRST_BUILD_SMOKE.md>
  screenshot SHA256 `201849b1368e06ebdbe3946c286312ea959e76f741aadf6517b782d57789fb88`.
- Public surface-return smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_SURFACE_RETURN_SMOKE.md>
  screenshot SHA256 `7836d3f526b71ca682b9bc9aa0d44ff979fc3b2b115d11f6dccbe2b8d858a9dd`.
- Public surface-movement smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_SURFACE_MOVEMENT_SMOKE.md>
  screenshot SHA256 `6efb01da9b025a97c1e0431f732fdd8357073e27aa838ec8d74cf0e1851f163b`.
- Runtime path: redownloaded repo-hosted `35a52259` ZIP under Xvfb, title -> class select -> surface gameplay, opened bunker with `E`, built Storage with `B`, returned to surface with `R`, then held `D` and `S` to prove surface movement.
- Runtime proof log SHA256: `2cff43c2e3daf2323afdc57a76b50087cfd5864e1724c8739c2ae192dadd73f4`.

## Public runtime save/Continue verification

A source-fresh UI smoke is available publicly through the support proof page and
screenshot below.

- Public package save/Continue proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_SAVE_CONTINUE_SMOKE.md>
- Loaded-bunker screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-save-continue-smoke.png>
- Loaded-bunker screenshot SHA256: `6983db7e762fd448ee6f587cb0ddcb95cd905e395310a06b8f0f0f97f68bb281`.
- Runtime path: redownloaded repo-hosted `35a52259` ZIP under Xvfb, title -> class select -> surface -> bunker, built Storage, saved, quit to title, then selected Continue back into the bunker.
- Save-file check: `save_autosave.json` existed, `current_realm_id` was `aftertimes`, and saved base rooms were `entry,workshop,storage`.
- Runtime proof log SHA256: `076af1a1651a303ca14e9a4fcef894cd242d6df6f600280988e4425840c16c4e`.

## Run on Linux

```bash
sha256sum the-aftertimes-realm1-linux-35a52259.zip
unzip the-aftertimes-realm1-linux-35a52259.zip
chmod +x the-aftertimes.x86_64
./the-aftertimes.x86_64
```

The hash should print `32b9dbdfcb1ccb77ac527e59bc6ee8f6aa6ff8bda6bb9a01ea4b2ad7bfbae6dd`.
