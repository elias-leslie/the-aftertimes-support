# Realm 1 Release Scope / Deferral Review

Status: public scope and deferral packet for legal/store/business review. It does **not** approve paid launch, pricing, platform setup, or privacy wording.

Use this as the decision checklist for the current paid-release review. Do not post secrets, tax IDs, payout details, private account data, or tokenized platform URLs in public issues.

## Build under review

- Public review release: <https://github.com/elias-leslie/the-aftertimes-support/releases/tag/realm1-review-a5392e7c>
- Linux review zip: <https://github.com/elias-leslie/the-aftertimes-support/releases/download/realm1-review-a5392e7c/the-aftertimes-realm1-linux-a5392e7c.zip>
- Zip SHA256: `4d25cd74e4212de86dd64c7e3fa9b4144d267b31d47192af3def51c276c0904e`
- Runtime/export commit: `a5392e7c`
- Scope: prerelease external-review package, not a public paid launch.

## Proposed release scope if reviewers approve

- Product: **The AfterTimes — Realm 1** as a paid first-chapter / Early Access candidate.
- Platform claim: **Linux only** until another platform has native runtime proof.
- Content claim: Realm 1 includes class select, surface survival, bunker building, NPC recruitment, crafting, Geothermal Reactor completion, Return Loop / Earth Remembers ending, post-credits crew finale, save/load, rebinding, readability controls, local JSONL telemetry, and Credits / Licenses panels.
- Support/contact claim: public project/support page plus public support/review issues.
- Privacy claim: local-only JSONL telemetry, no network analytics.

## Must be approved or explicitly deferred

| Area | Current evidence | Decision needed |
|---|---|---|
| External QA | Public QA tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/1> | External PASS, or accepted MIXED/deferral, for fresh unaided completion. |
| Art / animation / audio | Public art/audio tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/2> | External PASS, or accepted MIXED/deferral, after running-game plus artifact review. |
| Store/legal/business | Public legal/store tracker: <https://github.com/elias-leslie/the-aftertimes-support/issues/3> | PASS, or accepted MIXED/deferral, for this whole packet. |
| Store copy | Draft: <https://github.com/elias-leslie/the-aftertimes-support/blob/main/REALM1_STORE_DRAFT.md> | Approve descriptions, tags, Early Access wording, trailer outline, factsheet, and publication blockers. |
| Pricing | Draft base-price rationale is `$9.99 USD` in the store draft. | Approve base price, regional pricing, taxes, discounts, and platform fees. |
| Platform setup | No public app IDs, payout/tax setup, or release-owner fields are posted. | Complete outside the repo; record only non-secret status or approved deferral. |
| Public links/contact | Support page: <https://elias-leslie.github.io/the-aftertimes-support/>; support issues: <https://github.com/elias-leslie/the-aftertimes-support/issues> | Approve GitHub Pages/issues as website/support contact, or provide a dedicated inbox/platform website. |
| Privacy/telemetry | SECURITY/privacy notes and telemetry guide are public. | Approve local-only JSONL/no-network wording. |
| Platform claims | Linux proof exists; Windows artifact exists but native/Wine runtime execution is not approved; macOS/web/mobile are not in scope. | Publish Linux-only claims, or run/approve extra platform QA before claiming other platforms. |

## Proposed deferrals / scoped-out claims

These are proposed deferrals for reviewer approval, not automatic approvals:

- Windows runtime support: defer until native Windows or fixed Wine runtime proof exists. Do not sell or label a Windows build from the current evidence.
- macOS, web, and mobile: defer from the paid Realm 1 scope.
- Multiplayer/RTS hosting: defer from v1; current release is single-player.
- Realms 2-6 full playable scope: defer; paid candidate is Realm 1 / first chapter.
- Dedicated press inbox and social accounts: omit unless a public owner-approved inbox/profile is supplied; use the GitHub Pages support page and public issues only if reviewers accept that route.
- Platform account IDs, payout, tax, and private business details: handle outside public repos; never post secrets or private account data.
- Platform claims beyond proven Linux runtime: omit unless matching QA evidence is added.

## Verdict form

Submit the release legal/store/business verdict here:

<https://github.com/elias-leslie/the-aftertimes-support/issues/new?template=release_legal_store_review.yml>

Paid launch remains blocked until the three public trackers record PASS or accepted MIXED/deferral decisions.
