# Realm 1 Public Release Surface Return Smoke

Status: public source-fresh `682a0eb2` UI/gameplay smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-07 from the public repo-hosted support ZIP after redownload and SHA check:

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- ZIP SHA256: `432d450275e7e42f7b000c8a9e4b7d488c8bf72e273d4638f89d395144f2b719`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `0b1f2e59564ffeb6b4055e0ae6e56e11b3df6b2d365f8260a885260add24c671`
- Runtime/export commit: `682a0eb2`
- Built-Storage screenshot SHA256 before return: `361ccf94a5a0cca716d81c6462f1d8cc871c9bf71270f6f0df8980517ff140e2`
- Surface-return screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-surface-return-ui-smoke.png>
- Surface-return screenshot SHA256: `7328b786e79561dffa132fa8f46e597a666447247f4dbe9a52f5af97e28d6e8c`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach surface gameplay, entered the bunker with `E`, built Storage with `B`, pressed `R` to return to the surface, waited for the transition, and captured surface gameplay.

![Public release surface return UI smoke](public-release-surface-return-ui-smoke.png)

Visible result: the current repo-hosted public package returns from the built bunker to surface gameplay and renders `Radiation`, `Map`, `Inventory`, `Day 1`, `E/Enter Open bunker`, and the updated objective `Return to the surface and scout for Mira. Her arrow appears once her shelter is explored.`

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
