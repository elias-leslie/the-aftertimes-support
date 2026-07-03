# Realm 1 Public Release Class Select Smoke

Status: public release title-to-class-select UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-28b02d4d>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-28b02d4d/the-aftertimes-realm1-linux-28b02d4d.zip>
- Zip SHA256: `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `361db6d98ba211ffd5e1a769bb5867fc2b5bd161abeaf298616bafae463e0fac`
- Title screenshot SHA256 before input: `01f6c793a1c28810f8b7c2abcb58bcec4a2b55681ee9403cd06678a0924d552e`
- Class-select screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-class-select-ui-smoke.png>
- Class-select screenshot SHA256: `5a258eb8f91365dbbd4eaed316034be92f51f5ae30115b86f0de3339a6590836`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720, pressed `Enter` on `Wake the Shelter`, and captured the visible class-select screen.

![Public release class select UI smoke](public-release-class-select-ui-smoke.png)

Visible result: class select renders `Choose who wakes first`, `Survivor: Scout — Long Range`, and `Left or Right: Choose Survivor · Enter or Space: Wake the Shelter` from the published public release asset.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
