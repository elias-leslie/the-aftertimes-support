# Realm 1 Public Release UI Smoke

Status: previous public source-fresh `682a0eb2` UI/gameplay smoke proof. This is superseded lineage and does **not** replace the current agentic release gates.

Verified on 2026-07-07 from the public repo-hosted support ZIP after redownload and SHA check:

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- ZIP SHA256: `432d450275e7e42f7b000c8a9e4b7d488c8bf72e273d4638f89d395144f2b719`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `0b1f2e59564ffeb6b4055e0ae6e56e11b3df6b2d365f8260a885260add24c671`
- Runtime/export commit: `682a0eb2`
- UI smoke screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-title-ui-smoke.png>
- UI screenshot SHA256: `01f6c793a1c28810f8b7c2abcb58bcec4a2b55681ee9403cd06678a0924d552e`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile and captured the visible title screen.

![Public release title UI smoke](public-release-title-ui-smoke.png)

Visible result: title menu renders `THE AFTERTIMES`, `Wake the Shelter`, `Continue (no shelter record)`, `Credits / Licenses`, and no saved shelter records from a fresh temp profile.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
