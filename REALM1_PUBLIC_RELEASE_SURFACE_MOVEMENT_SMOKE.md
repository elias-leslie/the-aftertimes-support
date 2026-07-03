# Realm 1 Public Release Surface Movement Smoke

Status: public release surface-movement UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-a5392e7c/the-aftertimes-realm1-linux-a5392e7c.zip>
- Zip SHA256: `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `32a7d59ab5b556f0afc8725364f8f237ba9a39ca6ecd5d741222eaaa249689da`
- Before-movement screenshot SHA256: `f6bda3d24861c00f1a9c9216eb76277cac3e63aa35b287cb96aab207ab39a2c5`
- Surface-movement screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-surface-movement-ui-smoke.png>
- Surface-movement screenshot SHA256: `1becc44db18840c4fb23e72e92d0d0cb6b441499d6ab028d0e13f15186874b11`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach playable bunker UI, built Storage with `B`, pressed `R` to return to the surface, held `D` then `S`, and captured surface gameplay after movement.

![Public release surface movement UI smoke](public-release-surface-movement-ui-smoke.png)

Visible result: the before screenshot shows the player at the bunker entrance with `E/Enter Open bunker`; the movement screenshot shows the player displaced south-east from the bunker, the bunker prompt gone, the minimap marker shifted, and the surface HUD still rendering `Radiation`, `Map`, `Inventory`, `Day 1`, and `Health`.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
