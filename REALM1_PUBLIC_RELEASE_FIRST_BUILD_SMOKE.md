# Realm 1 Public Release First Build Smoke

Status: previous public source-fresh `682a0eb2` UI/gameplay smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-07 from the public repo-hosted support ZIP after redownload and SHA check:

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- ZIP SHA256: `432d450275e7e42f7b000c8a9e4b7d488c8bf72e273d4638f89d395144f2b719`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `0b1f2e59564ffeb6b4055e0ae6e56e11b3df6b2d365f8260a885260add24c671`
- Runtime/export commit: `682a0eb2`
- Surface gameplay-entry screenshot SHA256 before bunker entry: `c8eaff4374af396b24d85547b89ca0d109b47592a2de0813377f0a417fd03483`
- Bunker-entry screenshot SHA256 before build: `a855cc7f7a8c66d03c4dfbb10fddc5f9108df40186d08764f9d95b3de7182a1d`
- First-build screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-first-build-ui-smoke.png>
- First-build screenshot SHA256: `361ccf94a5a0cca716d81c6462f1d8cc871c9bf71270f6f0df8980517ff140e2`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach surface gameplay, pressed `E` at the bunker entrance, pressed `B` on the initial `Build Storage` prompt, and captured the built Storage room.

![Public release first build UI smoke](public-release-first-build-ui-smoke.png)

Visible result: the current repo-hosted public package builds the first Storage room and renders `Rooms: 3`, `Storage`, `Built Storage in the middle bunker bay.`, and the post-build objective `Return to the surface and scout for Mira. Her arrow appears once her shelter is explored.`

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
