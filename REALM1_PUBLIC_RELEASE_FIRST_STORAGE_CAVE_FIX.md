# Realm 1 Public First-Storage Unrepaired-Cave Fix Proof

Status: current public review package published; public redownload smoke passed; external QA/art/legal gates still open.

Current public review build:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-a5392e7c/the-aftertimes-realm1-linux-a5392e7c.zip>
- Zip SHA256: `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`
- Runtime/export commit: `a5392e7c`
- Linux executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- Godot pack SHA256: `32a7d59ab5b556f0afc8725364f8f237ba9a39ca6ecd5d741222eaaa249689da`

Why this refresh exists:

- The previous public package `realm1-review-d3fc7d09` was built before the first-Storage unrepaired-cave input fix.
- Fixed source proof: <https://github.com/elias-leslie/the-aftertimes/blob/main/docs/PLAYTEST_REPORTS/2026-07-03-first-storage-unrepaired-cave-build-v1.md>
- Fixed runtime screenshot SHA256: `54a3e51c9db39a684fb0113d5418e9e0c26bed3bf7a65645be28790ab39431f8`

Public package smoke:

- Public zip redownloaded from the release URL and matched SHA256 `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`.
- Redownloaded package headless smoke passed.
- Redownloaded package UI smoke reached title, class select, surface, bunker entry, then pressed `B` and built `Storage`.
- Public first-build screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-first-build-after-storage-fix.png>
- Public first-build screenshot SHA256: `0cc0742075f512451e6af54c3c68971f2a41e7a4df57f8007d0b90d7cec99389`

Result proven by the source/runtime fix: when an unrepaired ancient cave chamber is selected, pressing `B` for the first build creates `Storage` and leaves the damaged cave unconverted.

This is still a prerelease external-review package, not a public paid launch. External QA, art / animation / audio review, and legal / store / business review remain open until verdicts are recorded.
