# Realm 1 Public Release Surface Movement Smoke

Status: public source-fresh `35a52259` UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-07 from the public repo-hosted support ZIP after redownload and SHA check:

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-35a52259.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-35a52259.zip>
- ZIP SHA256: `32b9dbdfcb1ccb77ac527e59bc6ee8f6aa6ff8bda6bb9a01ea4b2ad7bfbae6dd`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `bbf55141c3851fe943be43c503e8dc16158c8edbec3fe5e3948315d40754ec3f`
- Runtime/export commit: `35a52259`
- Before-movement screenshot SHA256: `7836d3f526b71ca682b9bc9aa0d44ff979fc3b2b115d11f6dccbe2b8d858a9dd`
- Surface-movement screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-surface-movement-ui-smoke.png>
- Surface-movement screenshot SHA256: `6efb01da9b025a97c1e0431f732fdd8357073e27aa838ec8d74cf0e1851f163b`
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach surface gameplay, entered the bunker with `E`, built Storage with `B`, pressed `R` to return to the surface, held `D` then `S`, and captured surface gameplay after movement.

![Public release surface movement UI smoke](public-release-surface-movement-ui-smoke.png)

Visible result: the before screenshot shows the player at the bunker entrance with `E/Enter Open bunker`; the movement screenshot shows the player displaced away from the bunker, the bunker prompt gone, the minimap marker shifted, and the surface HUD still rendering `Radiation`, `Map`, `Inventory`, `Day 1`, `Health`, and the updated Storage -> Mira objective.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
