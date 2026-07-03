# Realm 1 Public Release First Build Smoke

Status: public release first-objective bunker build UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-28b02d4d>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-28b02d4d/the-aftertimes-realm1-linux-28b02d4d.zip>
- Zip SHA256: `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `361db6d98ba211ffd5e1a769bb5867fc2b5bd161abeaf298616bafae463e0fac`
- Before-build screenshot SHA256: `68159665179f223507127287cab93010bb4d5097df3fbc6fd61c0db5034f14a0`
- First-build screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-first-build-ui-smoke.png>
- First-build screenshot SHA256: `bdcf97b90f031d4bb0e944efcb3ebdb69d4e6cf38b99106bdf23cc134b5e2cca`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach playable bunker UI, pressed `B` on the initial `Build Storage` prompt, and captured the built Storage room.

![Public release first build UI smoke](public-release-first-build-ui-smoke.png)

Visible result: the published public release asset builds the first Storage room and renders `Rooms: 3`, `Storage`, `Built Storage in the middle bunker bay.`, and the post-build objective `Return to the surface and find Mira.`

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
