# Realm 1 Public Release Save / Continue Smoke

Status: public release save/continue UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-04 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-a5392e7c/the-aftertimes-realm1-linux-a5392e7c.zip>
- Zip SHA256: `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `32a7d59ab5b556f0afc8725364f8f237ba9a39ca6ecd5d741222eaaa249689da`
- Storage-built screenshot SHA256: `010df5e8cd1a5e586711a220b078fcd6c6e602d1825320124b95d7d3e7eb0e57`
- Saved pause-menu screenshot SHA256: `1184c8157fe1afe88e4ac4f61f6c372e1ee9713db57640c8138cab5bb44ed4e6`
- Title-after-quit screenshot SHA256: `df8cae6ccbf8391bf73b58d2404c6cc5e8d5bc67fb9c7dd27ec45fe2bb5ae41a`
- Loaded-bunker screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-save-continue-smoke.png>
- Loaded-bunker screenshot SHA256: `a13b9790abad2af75a1b4f56797771ab6e1ea02dc6b938266efbc682fdf8f264`
- Save-file check: `save_autosave.json` existed in a fresh temp profile, realm was `aftertimes`, and saved base rooms were `entry,workshop,storage`.
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach playable bunker UI, built Storage with `B`, opened pause, selected **Save Shelter Record**, quit to title, selected **Continue**, and captured the loaded bunker state.

![Public release save/continue smoke](public-release-save-continue-smoke.png)

Visible result: after Continue, the public package returns to the bunker with `Rooms: 3`, `Entry`, `Workshop`, `Storage`, the current first-run tutorial prompt, and the same carried supplies visible. The title screen before Continue showed `Continue: The AfterTimes · bunker`.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
