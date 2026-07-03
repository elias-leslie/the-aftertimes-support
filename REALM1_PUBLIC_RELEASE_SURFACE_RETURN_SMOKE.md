# Realm 1 Public Release Surface Return Smoke

Status: public release first-build-to-surface-return UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-28b02d4d>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-28b02d4d/the-aftertimes-realm1-linux-28b02d4d.zip>
- Zip SHA256: `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `361db6d98ba211ffd5e1a769bb5867fc2b5bd161abeaf298616bafae463e0fac`
- Built-Storage screenshot SHA256 before return: `bdcf97b90f031d4bb0e944efcb3ebdb69d4e6cf38b99106bdf23cc134b5e2cca`
- Surface-return screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-surface-return-ui-smoke.png>
- Surface-return screenshot SHA256: `f6bda3d24861c00f1a9c9216eb76277cac3e63aa35b287cb96aab207ab39a2c5`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach playable bunker UI, built Storage with `B`, pressed `R` to return to the surface, waited for the transition, and captured surface gameplay.

![Public release surface return UI smoke](public-release-surface-return-ui-smoke.png)

Visible result: the published public release asset returns from the built bunker to surface gameplay and renders `Radiation`, `Map`, `Inventory`, `Day 1`, `E/Enter Open bunker`, and the objective `Return to the surface and find Mira.`

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
