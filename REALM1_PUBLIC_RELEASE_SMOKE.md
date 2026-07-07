# Realm 1 Public Release Redownload Smoke

Status: superseded public GitHub Release asset integrity and runtime smoke proof. Current external review uses the repo-hosted `682a0eb2` ZIP in `REALM1_PUBLIC_REPO_DOWNLOAD_682A0EB2.md`. This does **not** replace external unaided QA, art/audio review, or legal/store approval.

Verified on 2026-07-03 from the public support-repo release URL:

- Release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Asset: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-a5392e7c/the-aftertimes-realm1-linux-a5392e7c.zip>
- Expected SHA256: `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`
- Actual SHA256 after redownload: `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`
- Extracted files: `the-aftertimes.x86_64`, `the-aftertimes.pck`, `build_manifest.json`, `REALM1_PLAYTEST_GUIDE.md`, `PLAYTEST_BUILD.md`, `README-LINUX-REVIEW.txt`
- Runtime smoke command: `./the-aftertimes.x86_64 --headless --quit-after 60`
- Runtime smoke result: `PASS`

Observed runtime output:

```text
Godot Engine v4.7.stable.official.5b4e0cb0f - https://godotengine.org
runtime_smoke=PASS
```

Reviewers should use the current `682a0eb2` repo-hosted ZIP for new source-fresh review, then run the game normally and submit verdicts through the public tracker issues. Paid launch remains blocked until the public trackers record PASS or accepted MIXED/deferral decisions.
