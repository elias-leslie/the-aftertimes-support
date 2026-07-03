# Realm 1 Public Release First Build Smoke

Status: public release first-objective bunker build UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-d3fc7d09>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-d3fc7d09/the-aftertimes-realm1-linux-d3fc7d09.zip>
- Zip SHA256: `5bfc0816d402dd94bfe0db16a36d283a55b63328581cc8a29f3b94245eb425fa`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `6c5ef6daebfa5b7b3701d750cac1203bac023cafbc9ec4f98fac34e7a0f1d0f8`
- Before-build screenshot SHA256: `434506be38dcd1eeb616e3545ab42dcb9e0db41b4c2e9ff380d12267c8b4cd19`
- First-build screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-first-build-ui-smoke.png>
- First-build screenshot SHA256: `f9922072c4e93879d44ebf876830d3dfb4e87806978a835c0f253f3dce924497`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach playable bunker UI, pressed `B` on the initial `Build Storage` prompt, and captured the built Storage room.

![Public release first build UI smoke](public-release-first-build-ui-smoke.png)

Visible result: the published public release asset builds the first Storage room and renders `Rooms: 3`, `Storage`, `Built Storage in the middle bunker bay.`, and the post-build objective `Return to the surface and find Mira.`

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
