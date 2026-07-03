# Realm 1 Public Release Save / Continue Smoke

Status: public release save/continue UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release zip after redownload and SHA check:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-28b02d4d>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-28b02d4d/the-aftertimes-realm1-linux-28b02d4d.zip>
- Zip SHA256: `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `361db6d98ba211ffd5e1a769bb5867fc2b5bd161abeaf298616bafae463e0fac`
- Storage-built screenshot SHA256: `80b11bf6ee0315c4277187e916330f88e2df5422e704fe5ac658a60c9cce401f`
- Saved pause-menu screenshot SHA256: `ab3695f4b4c25fce17f8eb00cc2b623720a1ad92046114e8f780928bc0dee908`
- Title-after-quit screenshot SHA256: `df8cae6ccbf8391bf73b58d2404c6cc5e8d5bc67fb9c7dd27ec45fe2bb5ae41a`
- Loaded-bunker screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-save-continue-smoke.png>
- Loaded-bunker screenshot SHA256: `7016dafec7e0d96c7ccddf37756bafb15d2977738fe8ed2835fd10f47386e1fd`
- Save-file check: `save_autosave.json` existed in a fresh temp profile, realm was `aftertimes`, and saved base rooms were `entry,workshop,storage`.
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach playable bunker UI, built Storage with `B`, opened pause, selected **Save Shelter Record**, quit to title, selected **Continue**, and captured the loaded bunker state.

![Public release save/continue smoke](public-release-save-continue-smoke.png)

Visible result: after Continue, the public package returns to the bunker with `Rooms: 3`, `Entry`, `Workshop`, `Storage`, the current first-run tutorial prompt, and the same carried supplies visible. The title screen before Continue showed `Continue: The AfterTimes · bunker`.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
