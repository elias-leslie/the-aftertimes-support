# The AfterTimes Support

Public support and release-review contact point for **The AfterTimes**.

- Public support page: <https://elias-leslie.github.io/the-aftertimes-support/>
- Game repository: <https://github.com/elias-leslie/the-aftertimes>
- Support/issues: <https://github.com/elias-leslie/the-aftertimes-support/issues>
- Security/privacy notes: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/SECURITY.md>
- License: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/LICENSE>
- Notice: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/NOTICE>

Current public review build:

- Release page: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-28b02d4d>
- Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-28b02d4d/the-aftertimes-realm1-linux-28b02d4d.zip>
- Public playtest guide: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PLAYTEST_GUIDE.md>
- Public automated completion proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_AUTOMATED_COMPLETION_PROOF.md>
- Public release redownload smoke proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_SMOKE.md>
- Public release UI smoke proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_UI_SMOKE.md>
- Public release class-select smoke proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_CLASS_SELECT_SMOKE.md>
- Public release gameplay-entry smoke proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_GAMEPLAY_ENTRY_SMOKE.md>
- Public release first-build smoke proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_FIRST_BUILD_SMOKE.md>
- Public first-Storage unrepaired-cave fix proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_FIRST_STORAGE_CAVE_FIX.md>
- Public release surface-return smoke proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_SURFACE_RETURN_SMOKE.md>
- Public release surface-movement smoke proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_RELEASE_SURFACE_MOVEMENT_SMOKE.md>
- Public telemetry review guide: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_TELEMETRY_REVIEW_GUIDE.md>
- Public launch screenshot contact sheet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/launch-screenshots-v2-contact.png>
- Public capsule/key-art family proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/steam-capsule-family-v1-proof.png>
- Public art / audio review packet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_ART_AUDIO_REVIEW_PACKET.md>
- Public store copy draft: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_STORE_DRAFT.md>
- Public release scope / deferral review: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_RELEASE_SCOPE_DEFERRALS.md>
- Public Credits / Licenses proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_CREDITS_LICENSES_PROOF.md>
- SHA256: `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`
- Scope: prerelease external-review package, not a public paid launch.

Run on Linux:

1. Download the Linux review zip.
2. Optional hash check: `sha256sum the-aftertimes-realm1-linux-28b02d4d.zip` should print `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`.
3. Unzip it, keep `the-aftertimes.x86_64` and `the-aftertimes.pck` in the same folder, then run: `chmod +x the-aftertimes.x86_64 && ./the-aftertimes.x86_64`.

Public review forms:

Review form placeholders use the current public package `realm1-review-28b02d4d` and zip SHA `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`.

- External QA playtest report: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=playtest_report.yml>
- Art / animation / audio review: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=art_animation_audio_review.yml>
- Legal / store / business review: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=release_legal_store_review.yml>

Public blocker trackers:

- External QA verdict tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/1>
- Art / animation / audio verdict tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/2>
- Legal / store / business verdict tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/3>

Current external release gates:

- External QA: open until a fresh unaided completion playtest reports PASS, or an accepted MIXED/deferral, through the playtest form.
- Art / animation / audio: open until running-game plus artifact review reports PASS, or an accepted MIXED/deferral, through the art/audio form.
- Legal / store / business: open until store/legal/platform/pricing fields are approved, or accepted deferrals are listed, through the legal/store form.

For playtest feedback, art/audio review notes, store/legal review notes, or launch-support questions, open an issue here and include the build hash or review package URL you used.

Review builds may write local-only JSONL playtest events for player deaths, room builds, and reactor completions. No network analytics are sent. Do not post secrets, private account information, tax/payment details, unreleased credentials, or unredacted local logs/paths.
