# Realm 1 Public Package Save / Continue Smoke

Status: public package save/Continue UI smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-07 from the public repo-hosted source-fresh Linux review zip after redownload and SHA check:

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-35a52259.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-35a52259.zip>
- ZIP SHA256: `32b9dbdfcb1ccb77ac527e59bc6ee8f6aa6ff8bda6bb9a01ea4b2ad7bfbae6dd`
- ZIP bytes: `63,381,905`
- Runtime/export commit: `35a52259`
- Executable SHA256: `3154bb4465f616e24b811dd576e9230022872cd80f8d5ab854efed2716b926d4`
- PCK SHA256: `bbf55141c3851fe943be43c503e8dc16158c8edbec3fe5e3948315d40754ec3f`
- Storage-built screenshot SHA256: `8c6b4f164664164ada58de4ffc93d525225c18037b299326469e42470c64b1f0`
- Saved pause-menu screenshot SHA256: `a250bf574a71b0f1bf60d164783a0723c6a56e91692cfae290666eb130235dfd`
- Title-after-quit screenshot SHA256: `df8cae6ccbf8391bf73b58d2404c6cc5e8d5bc67fb9c7dd27ec45fe2bb5ae41a`
- Loaded-bunker screenshot: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/public-release-save-continue-smoke.png>
- Loaded-bunker screenshot SHA256: `6983db7e762fd448ee6f587cb0ddcb95cd905e395310a06b8f0f0f97f68bb281`
- Runtime proof log SHA256: `076af1a1651a303ca14e9a4fcef894cd242d6df6f600280988e4425840c16c4e`
- Save-file check: `save_autosave.json` existed in a fresh temp profile, `current_realm_id` was `aftertimes`, and saved base rooms were `entry,workshop,storage`.
- Runtime mode: launched the extracted public Linux executable under Xvfb at 1280x720 from a fresh temp profile, used keyboard input to reach playable bunker UI, built Storage with `B`, opened pause, selected **Save Shelter Record**, quit to title, selected **Continue**, and captured the loaded bunker state.

![Public package save/continue smoke](public-release-save-continue-smoke.png)

Visible result: after Continue, the public `35a52259` package returns to the bunker with `Rooms: 3`, `Entry`, `Workshop`, `Storage`, the current Storage -> Mira tutorial prompt, and the same carried supplies visible. The title screen before Continue showed `Continue: The AfterTimes · bunker`.

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
