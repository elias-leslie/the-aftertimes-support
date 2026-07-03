# Realm 1 Public First-Storage Unrepaired-Cave Fix Proof

Status: current public review package published; public redownload smoke passed; external QA/art/legal gates still open.

Current public review build:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-28b02d4d>
- Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-28b02d4d/the-aftertimes-realm1-linux-28b02d4d.zip>
- Zip SHA256: `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`
- Runtime/export commit: `28b02d4d956256df5372f598c6bcd3f9b0e11b14`
- Linux executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- Godot pack SHA256: `361db6d98ba211ffd5e1a769bb5867fc2b5bd161abeaf298616bafae463e0fac`

Why this refresh exists:

- The previous public package `realm1-review-d3fc7d09` was built before the first-Storage unrepaired-cave input fix.
- Fixed source proof: <https://github.com/elias-leslie/the-aftertimes/blob/main/docs/PLAYTEST_REPORTS/2026-07-03-first-storage-unrepaired-cave-build-v1.md>
- Fixed runtime screenshot SHA256: `54a3e51c9db39a684fb0113d5418e9e0c26bed3bf7a65645be28790ab39431f8`

Public package smoke:

- Public zip redownloaded from the release URL and matched SHA256 `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`.
- Redownloaded package headless smoke passed.
- Redownloaded package UI smoke reached title, class select, surface, bunker entry, then pressed `B` and built `Storage`.
- Public first-build screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-first-build-after-storage-fix.png>
- Public first-build screenshot SHA256: `f2549a765945490930e9a49759b8efa8c6afdee853c6792727bf41b3656f6438`

Result proven by the source/runtime fix: when an unrepaired ancient cave chamber is selected, pressing `B` for the first build creates `Storage` and leaves the damaged cave unconverted.

This is still a prerelease external-review package, not a public paid launch. External QA, art / animation / audio review, and legal / store / business review remain open until verdicts are recorded.
