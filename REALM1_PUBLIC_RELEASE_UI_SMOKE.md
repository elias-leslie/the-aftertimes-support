# Realm 1 Public Release UI Smoke

Status: public release UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-d3fc7d09>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-d3fc7d09/the-aftertimes-realm1-linux-d3fc7d09.zip>
- Zip SHA256: `5bfc0816d402dd94bfe0db16a36d283a55b63328581cc8a29f3b94245eb425fa`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `6c5ef6daebfa5b7b3701d750cac1203bac023cafbc9ec4f98fac34e7a0f1d0f8`
- UI smoke screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-title-ui-smoke.png>
- UI screenshot SHA256: `eaef828842c144b78626273e9a5544d07c6254bb23afe675a7cd7a1b11614d46`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 and captured the visible title screen.

![Public release title UI smoke](public-release-title-ui-smoke.png)

Visible result: title menu renders `THE AFTERTIMES`, `Wake the Shelter`, `Credits / Licenses`, and no saved shelter records from a fresh temp profile.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
