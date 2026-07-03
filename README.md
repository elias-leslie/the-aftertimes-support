# The AfterTimes Support

Public support and release-review contact point for **The AfterTimes**.

- Public support page: <https://elias-leslie.github.io/the-aftertimes-support/>
- Game repository: <https://github.com/elias-leslie/the-aftertimes>
- Support/issues: <https://github.com/elias-leslie/the-aftertimes-support/issues>
- Security/privacy notes: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/SECURITY.md>
- License: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/LICENSE>
- Notice: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/NOTICE>

Current public review build:

- Release page: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-d3fc7d09>
- Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-d3fc7d09/the-aftertimes-realm1-linux-d3fc7d09.zip>
- Public playtest guide: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PLAYTEST_GUIDE.md>
- Public launch screenshot contact sheet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/launch-screenshots-v2-contact.png>
- Public capsule/key-art family proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/steam-capsule-family-v1-proof.png>
- Public art / audio review packet: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_ART_AUDIO_REVIEW_PACKET.md>
- Public store copy draft: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_STORE_DRAFT.md>
- Public Credits / Licenses proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_CREDITS_LICENSES_PROOF.md>
- SHA256: `5bfc0816d402dd94bfe0db16a36d283a55b63328581cc8a29f3b94245eb425fa`
- Scope: prerelease external-review package, not a public paid launch.

Run on Linux:

1. Download the Linux review zip.
2. Optional hash check: `sha256sum the-aftertimes-realm1-linux-d3fc7d09.zip` should print `5bfc0816d402dd94bfe0db16a36d283a55b63328581cc8a29f3b94245eb425fa`.
3. Unzip it, keep `the-aftertimes.x86_64` and `the-aftertimes.pck` in the same folder, then run: `chmod +x the-aftertimes.x86_64 && ./the-aftertimes.x86_64`.

Public review forms:

- External QA playtest report: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=playtest_report.yml>
- Art / animation / audio review: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=art_animation_audio_review.yml>
- Legal / store / business review: <https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=release_legal_store_review.yml>

Current external release gates:

- External QA: open until a fresh unaided completion playtest reports PASS, or an accepted MIXED/deferral, through the playtest form.
- Art / animation / audio: open until running-game plus artifact review reports PASS, or an accepted MIXED/deferral, through the art/audio form.
- Legal / store / business: open until store/legal/platform/pricing fields are approved, or accepted deferrals are listed, through the legal/store form.

For playtest feedback, art/audio review notes, store/legal review notes, or launch-support questions, open an issue here and include the build hash or review package URL you used.

Review builds may write local-only JSONL playtest events for player deaths, room builds, and reactor completions. No network analytics are sent. Do not post secrets, private account information, tax/payment details, unreleased credentials, or unredacted local logs/paths.
