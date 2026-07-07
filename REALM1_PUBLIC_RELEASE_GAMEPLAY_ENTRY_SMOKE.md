# Realm 1 Public Release Gameplay Entry Smoke

Status: previous public source-fresh `682a0eb2` UI/gameplay smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-07 from the public repo-hosted support ZIP after redownload and SHA check:

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- ZIP SHA256: `432d450275e7e42f7b000c8a9e4b7d488c8bf72e273d4638f89d395144f2b719`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `0b1f2e59564ffeb6b4055e0ae6e56e11b3df6b2d365f8260a885260add24c671`
- Runtime/export commit: `682a0eb2`
- Title screenshot SHA256 before input: `01f6c793a1c28810f8b7c2abcb58bcec4a2b55681ee9403cd06678a0924d552e`
- Class-select screenshot SHA256 before gameplay entry: `e5ae3082f76632867e2ebf4c8b908e4a61f6028b90733cb1246de24dd750b807`
- Gameplay-entry screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-gameplay-entry-ui-smoke.png>
- Gameplay-entry screenshot SHA256: `c8eaff4374af396b24d85547b89ca0d109b47592a2de0813377f0a417fd03483`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, pressed `Return` on `Wake the Shelter`, let class-select settle, sent `Space` to confirm Scout, waited for surface gameplay, and captured the first playable surface screen.

![Public release gameplay entry UI smoke](public-release-gameplay-entry-ui-smoke.png)

Visible result: the current repo-hosted public package leaves the title/class-select UI and renders top-down surface gameplay with `Radiation`, `Map`, `Inventory`, `Day 1`, the Scout HUD, rain/fog, the bunker entrance, and the Scout intro objective text visible.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
