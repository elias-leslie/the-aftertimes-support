# Realm 1 Public Release Surface Return Smoke

Status: public release first-build-to-surface-return UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-a5392e7c/the-aftertimes-realm1-linux-a5392e7c.zip>
- Zip SHA256: `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `32a7d59ab5b556f0afc8725364f8f237ba9a39ca6ecd5d741222eaaa249689da`
- Built-Storage screenshot SHA256 before return: `0cc0742075f512451e6af54c3c68971f2a41e7a4df57f8007d0b90d7cec99389`
- Surface-return screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-surface-return-ui-smoke.png>
- Surface-return screenshot SHA256: `f6bda3d24861c00f1a9c9216eb76277cac3e63aa35b287cb96aab207ab39a2c5`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach playable bunker UI, built Storage with `B`, pressed `R` to return to the surface, waited for the transition, and captured surface gameplay.

![Public release surface return UI smoke](public-release-surface-return-ui-smoke.png)

Visible result: the published public release asset returns from the built bunker to surface gameplay and renders `Radiation`, `Map`, `Inventory`, `Day 1`, `E/Enter Open bunker`, and the objective `Return to the surface and find Mira.`

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
