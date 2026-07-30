# LegalOn

LegalOn Technologies builds AI software for in-house legal teams, corporate legal operations, and law firms — AI contract review and redlining, contract playbooks, matter management, a contract data vault, translation, entity and board management, and agentic legal workflows, with a Microsoft Word integration. The company operates in Japan (legalontech.jp, originally LegalForce) and the United States (legalontech.com), alongside a sibling product family for governance (GovernOn), sales (DealOn), HR (WorkOn), and marketing compliance (DocumentOn).

## API

LegalOn publishes a REST contract API, announced 2026-07-13 as the second phase of its API connectivity: contract file upload/retrieve/update/delete, contract metadata register/update/retrieve, related-document linking, and contract listing — for integration with contract management systems, CRM, and BI tooling. Authentication is OAuth 2.0 `client_credentials`, scoped to workspaces where the caller holds an appropriate role.

There is **no public API reference, developer portal, OpenAPI, SDK, CLI, or MCP server**. The `api.legalontech.com` host resolves but returns 403 to all unauthenticated requests. API access is arranged with the vendor.

## Artifacts

| Artifact | File |
|---|---|
| Authentication | `authentication/legalon-authentication.yml` |
| Conventions | `conventions/legalon-conventions.yml` |
| Conformance | `conformance/legalon-conformance.yml` |
| Lifecycle | `lifecycle/legalon-lifecycle.yml` |
| Changelog | `changelog/legalon-changelog.yml` |
| Domain security | `security/legalon-domain-security.yml` |
| Trust center | `security/legalon-trust-center.yml` |
| Well-known probe | `well-known/legalon-well-known.yml` |
| llms.txt | `llms/legalon-llms.txt` |

## Trust and operations

SOC 2 Type II, ISO/IEC 27001:2022, ISO/IEC 27017:2015, GDPR and CCPA practices — https://trust.legalontech.com/ · Status page https://status.legalontech.com/ · No `/.well-known/security.txt` and no published vulnerability disclosure or bug bounty program was found.

Backed by: Hongshan, SoftBank Vision Fund — https://www.legalontech.com/
