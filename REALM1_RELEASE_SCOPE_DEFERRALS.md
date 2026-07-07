# Realm 1 Release Scope / Deferral Review

Status: scoped release decision packet. It approves the repo-hosted Linux public package scope and explicitly defers paid storefront launch, pricing, platform setup, and non-Linux platform claims.

Use this as the decision checklist for the current paid-release review. Do not post secrets, tax IDs, payout details, private account data, or tokenized platform URLs in public issues.

## Build under review

- Repo-hosted Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/raw/main/downloads/the-aftertimes-realm1-linux-b1e41bab.zip>
- Download file in repository: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/downloads/the-aftertimes-realm1-linux-b1e41bab.zip>
- Public package proof: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_PUBLIC_REPO_DOWNLOAD_B1E41BAB.md>
- Superseded GitHub Release page: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Zip SHA256: `296aa58f7992a78486aee7e7ef39bedf266aefe968ce4f870d0442bc9b581621`
- ZIP bytes: `63,586,751`
- Runtime/export commit: `b1e41bab`
- Scope: public repo-hosted Linux package release. It is not a Steam/itch paid launch.

## Approved release scope

- Product: **The AfterTimes — Realm 1** as a public Linux first-chapter package.
- Platform claim: **Linux only** until another platform has native/fixed-runtime proof.
- Content claim: Realm 1 includes class select, surface survival, bunker building, NPC recruitment, crafting, Geothermal Reactor completion, Return Loop / Earth Remembers ending, post-credits crew finale, save/load, rebinding, readability controls, local JSONL telemetry, and Credits / Licenses panels.
- Support/contact claim: public project/support page plus public support/review issues.
- Privacy claim: local-only JSONL telemetry, no network analytics.

## Gate decisions

| Area | Current evidence | Decision needed |
|---|---|---|
| Completion QA | Current deterministic completion proof plus public QA tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/1> | Current deterministic proof is `PASS`; reopen only on concrete failed runtime evidence or accepted scope change. |
| Art / animation / audio | Public art/audio tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/2> | External PASS, or accepted MIXED/deferral, after running-game plus artifact review. |
| Store/legal/business | Public legal/store tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/3>; ship-scope decision: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_SHIP_READY_SCOPE_DECISION.md> | PASS for repo-hosted Linux package; paid storefront fields are deferred. |
| Store copy | Draft: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_STORE_DRAFT.md> | PASS for current support-page/package scope; revisit for paid storefront copy. |
| Pricing | Draft future paid-store base-price rationale is `$9.99 USD` in the store draft. | DEFERRED; no storefront price is needed for current repo-hosted package. |
| Platform setup | No public app IDs, payout/tax setup, or release-owner fields are needed for the repo-hosted package. | DEFERRED until paid storefront/platform release. |
| Public links/contact | Support page: <https://elias-leslie.github.io/the-aftertimes-support/>; support issues: <https://github.com/elias-leslie/the-aftertimes-support/issues> | PASS for current scope; dedicated inbox/platform website deferred. |
| Privacy/telemetry | SECURITY/privacy notes and telemetry guide are public. | PASS for current scope: local-only JSONL/no-network wording. |
| Platform claims | Linux proof exists; Windows artifact exists but native/Wine runtime execution is not approved; macOS/web/mobile are not in scope. | PASS for Linux-only claims; other platform claims deferred. |

## Proposed deferrals / scoped-out claims

These deferrals are approved for the current repo-hosted Linux ship scope:

- Windows runtime support: defer until native Windows or fixed Wine runtime proof exists. Do not sell or label a Windows build from the current evidence.
- macOS, web, and mobile: defer from the paid Realm 1 scope.
- Multiplayer/RTS hosting: defer from v1; current release is single-player.
- Realms 2-6 full playable scope: defer; paid candidate is Realm 1 / first chapter.
- Dedicated press inbox and social accounts: omit unless a public owner-approved inbox/profile is supplied; use the GitHub Pages support page and public issues only if reviewers accept that route.
- Platform account IDs, payout, tax, and private business details: handle outside public repos; never post secrets or private account data.
- Platform claims beyond proven Linux runtime: omit unless matching QA evidence is added.

## Verdict

The repo-hosted Linux package is ship-ready under this scoped decision. Paid storefront launch remains a future gate and should use the release legal/store/business form when that scope opens:

<https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=release_legal_store_review.yml>
