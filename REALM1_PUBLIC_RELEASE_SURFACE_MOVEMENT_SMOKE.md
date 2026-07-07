# Realm 1 Public Release Surface Movement Smoke

Status: previous public source-fresh `682a0eb2` UI/gameplay smoke proof. This is superseded lineage and does **not** replace the current agentic release gates.

Verified on 2026-07-07 from the public repo-hosted support ZIP after redownload and SHA check:

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-682a0eb2.zip>
- ZIP SHA256: `432d450275e7e42f7b000c8a9e4b7d488c8bf72e273d4638f89d395144f2b719`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `0b1f2e59564ffeb6b4055e0ae6e56e11b3df6b2d365f8260a885260add24c671`
- Runtime/export commit: `682a0eb2`
- Before-movement screenshot SHA256: `7328b786e79561dffa132fa8f46e597a666447247f4dbe9a52f5af97e28d6e8c`
- Surface-movement screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-surface-movement-ui-smoke.png>
- Surface-movement screenshot SHA256: `5bd24b8c5639695bc203b4040de479c4ab836f5e0cc4cd555bdd452bc0ae8135`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach surface gameplay, entered the bunker with `E`, built Storage with `B`, pressed `R` to return to the surface, held `D` then `S`, and captured surface gameplay after movement.

![Public release surface movement UI smoke](public-release-surface-movement-ui-smoke.png)

Visible result: the before screenshot shows the player at the bunker entrance with `E/Enter Open bunker`; the movement screenshot shows the player displaced away from the bunker, the bunker prompt gone, the minimap marker shifted, and the surface HUD still rendering `Radiation`, `Map`, `Inventory`, `Day 1`, `Health`, and the updated Storage -> Mira objective.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
