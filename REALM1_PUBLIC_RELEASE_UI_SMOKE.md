# Realm 1 Public Release UI Smoke

Status: public release UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-a5392e7c/the-aftertimes-realm1-linux-a5392e7c.zip>
- Zip SHA256: `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `32a7d59ab5b556f0afc8725364f8f237ba9a39ca6ecd5d741222eaaa249689da`
- UI smoke screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-title-ui-smoke.png>
- UI screenshot SHA256: `01f6c793a1c28810f8b7c2abcb58bcec4a2b55681ee9403cd06678a0924d552e`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 and captured the visible title screen.

![Public release title UI smoke](public-release-title-ui-smoke.png)

Visible result: title menu renders `THE AFTERTIMES`, `Wake the Shelter`, `Credits / Licenses`, and no saved shelter records from a fresh temp profile.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
