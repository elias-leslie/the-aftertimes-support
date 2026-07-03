# Realm 1 Public Release Surface Return Smoke

Status: public release first-build-to-surface-return UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-d3fc7d09>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-d3fc7d09/the-aftertimes-realm1-linux-d3fc7d09.zip>
- Zip SHA256: `5bfc0816d402dd94bfe0db16a36d283a55b63328581cc8a29f3b94245eb425fa`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `6c5ef6daebfa5b7b3701d750cac1203bac023cafbc9ec4f98fac34e7a0f1d0f8`
- Built-Storage screenshot SHA256 before return: `6d638e614024b040c2522a7bdbe54e96264ef217c0e4eb824874eaa6fbf1cd28`
- Surface-return screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-surface-return-ui-smoke.png>
- Surface-return screenshot SHA256: `023a77af4317bed6ff1540adeb7f4c741b84e99d7ad37c5149f6fae8747579b6`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach playable bunker UI, built Storage with `B`, pressed `R` to return to the surface, waited for the transition, and captured surface gameplay.

![Public release surface return UI smoke](public-release-surface-return-ui-smoke.png)

Visible result: the published public release asset returns from the built bunker to surface gameplay and renders `Radiation`, `Map`, `Inventory`, `Day 1`, `E/Enter Open bunker`, and the objective `Return to the surface and find Mira.`

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
