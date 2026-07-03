# Realm 1 Public Release Redownload Smoke

Status: public release asset integrity and runtime smoke proof. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release URL:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-28b02d4d>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-28b02d4d/the-aftertimes-realm1-linux-28b02d4d.zip>
- Expected SHA256: `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`
- Actual SHA256 after redownload: `5edeb25c0f80cd2a8a84fd061c790acadf31a9da04c86cb4b5a337bdfa5b4e33`
- Extracted files: `the-aftertimes.x86_64`, `the-aftertimes.pck`, `build_manifest.json`, `REALM1_PLAYTEST_GUIDE.md`, `PLAYTEST_BUILD.md`, `README-LINUX-REVIEW.txt`
- Runtime smoke command: `./the-aftertimes.x86_64 --headless --quit-after 60`
- Runtime smoke result: `PASS`

Observed runtime output:

```text
Godot Engine v4.7.stable.official.5b4e0cb0f - https://godotengine.org
runtime_smoke=PASS
```

Reviewers should still run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
