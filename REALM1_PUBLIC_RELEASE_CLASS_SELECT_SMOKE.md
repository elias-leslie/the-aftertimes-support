# Realm 1 Public Release Class Select Smoke

Status: public release title-to-class-select UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-a5392e7c/the-aftertimes-realm1-linux-a5392e7c.zip>
- Zip SHA256: `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `32a7d59ab5b556f0afc8725364f8f237ba9a39ca6ecd5d741222eaaa249689da`
- Title screenshot SHA256 before input: `01f6c793a1c28810f8b7c2abcb58bcec4a2b55681ee9403cd06678a0924d552e`
- Class-select screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-class-select-ui-smoke.png>
- Class-select screenshot SHA256: `25e28b20e5ec5030330b178e806dd9791fd68116b09e73545fe2c139d1f927e4`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720, pressed `Enter` on `Wake the Shelter`, and captured the visible class-select screen.

![Public release class select UI smoke](public-release-class-select-ui-smoke.png)

Visible result: class select renders `Choose who wakes first`, `Survivor: Scout — Long Range`, and `Left or Right: Choose Survivor · Enter or Space: Wake the Shelter` from the published public release asset.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
