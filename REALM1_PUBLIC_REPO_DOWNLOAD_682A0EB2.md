# Realm 1 Public Repo-Hosted Review Package 682a0eb2

Status: **source-fresh public review package**, not a paid public launch.

This package is hosted in the support repository as the current external-review
ZIP while GitHub Release asset publication for `682a0eb2` is pending. Use this
ZIP for new external review. The prior repo-hosted `35a52259` package and the
older GitHub Release asset `realm1-review-a5392e7c` remain superseded evidence
lineage only.

## Download

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- ZIP filename: `the-aftertimes-realm1-linux-682a0eb2.zip`
- ZIP SHA256: `432d450275e7e42f7b000c8a9e4b7d488c8bf72e273d4638f89d395144f2b719`
- ZIP bytes: `63,382,521`
- Runtime/export commit: `682a0eb2`

## Inner export identity

- Linux executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- Linux executable bytes: `73,433,400`
- Linux `.pck` SHA256: `0b1f2e59564ffeb6b4055e0ae6e56e11b3df6b2d365f8260a885260add24c671`
- Linux `.pck` bytes: `36,554,412`

## Source-local pre-publication proof summary

The support repo exposes the non-secret artifacts reviewers need publicly;
deeper source-local manifests and proof logs remain in the game repository.
Publicly visible pre-publication evidence:

- Launch screenshot contact: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/launch-screenshots-v2-contact-682a0eb2.png>
- Launch screenshot contact SHA256: `8500cbdf66dda8b153bae3f5642fc1ac20f04542e1c1dce644bcbfe8448bd146`
- Exported-package pause menu proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-package-return-to-surface-control-label-682a0eb2.png>
- Exported-package pause menu screenshot SHA256: `7cc4e689feb67239863479b51554c7c91c64521e653fe27b82f7a635b9fa7d05`
- Source-local Return to Surface control-label screenshot SHA256:
  `938c37eb173de10e49f4e973372b2f39190c61f53bd3a596a06c30461858765a`.
- Current package headless smoke: ZIP SHA matched, extracted inner hashes matched,
  and `./the-aftertimes.x86_64 --headless --quit-after 60` completed.

## Public verification

Public redownload verification is summarized here so external reviewers do not
need private/source-repo access.

- Public ZIP fetch: pending until this support repository update is pushed.
- Public ZIP SHA256: pending.
- Extracted inner hash check: pending.
- Extracted Linux build headless smoke: pending.
- Public support page fetch/browser check: pending.

## Public runtime basic-smoke lineage

The current `682a0eb2` ZIP has package-level headless and visible pause-menu
proof above. The public title/class-select/gameplay/first-build/surface/save
smoke screenshots below remain the prior source-fresh `35a52259` lineage until
those longer public smokes are refreshed on `682a0eb2`; use them only as
supplemental context, not as a substitute for running the current ZIP.

- Prior public title UI smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_UI_SMOKE.md>
  screenshot SHA256 `01f6c793a1c28810f8b7c2abcb58bcec4a2b55681ee9403cd06678a0924d552e`.
- Prior public class-select smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_CLASS_SELECT_SMOKE.md>
  screenshot SHA256 `1d3a7234972d0586a1b2f188b2e80bbacdc666fb4e6816a22bba311b2dbd6e94`.
- Prior public surface gameplay-entry smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_GAMEPLAY_ENTRY_SMOKE.md>
  screenshot SHA256 `5c0bfa073f9919792e1085f001a725b71219c457484a00985396d9ccde3b8bd2`.
- Prior public first-Storage build smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_FIRST_BUILD_SMOKE.md>
  screenshot SHA256 `201849b1368e06ebdbe3946c286312ea959e76f741aadf6517b782d57789fb88`.
- Prior public surface-return smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_SURFACE_RETURN_SMOKE.md>
  screenshot SHA256 `7836d3f526b71ca682b9bc9aa0d44ff979fc3b2b115d11f6dccbe2b8d858a9dd`.
- Prior public surface-movement smoke: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_SURFACE_MOVEMENT_SMOKE.md>
  screenshot SHA256 `6efb01da9b025a97c1e0431f732fdd8357073e27aa838ec8d74cf0e1851f163b`.
- Prior public save/Continue proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_SAVE_CONTINUE_SMOKE.md>
  screenshot SHA256 `6983db7e762fd448ee6f587cb0ddcb95cd905e395310a06b8f0f0f97f68bb281`.

## Run on Linux

```bash
sha256sum the-aftertimes-realm1-linux-682a0eb2.zip
unzip the-aftertimes-realm1-linux-682a0eb2.zip
chmod +x the-aftertimes.x86_64
./the-aftertimes.x86_64
```

The hash should print `432d450275e7e42f7b000c8a9e4b7d488c8bf72e273d4638f89d395144f2b719`.
