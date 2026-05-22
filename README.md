# Frontegg

Frontegg is a customer identity and access management (CIAM) platform for B2B SaaS — self-serve authentication, multi-tenancy, role-based access control, single sign-on, SCIM provisioning, entitlements, and an admin portal that ships with the product. This repository is the API Evangelist profile of Frontegg, indexing its public API surface and producing API Commons / Naftiko / FinOps artifacts derived from Frontegg's published OpenAPI specifications.

- Provider site: https://frontegg.com
- Developer docs: https://developers.frontegg.com
- API reference overview: https://developers.frontegg.com/ciam/api/overview
- OpenAPI repository: https://github.com/frontegg/openapi-public
- Status page: https://status.frontegg.com (Atom: `/history.atom`, RSS: `/history.rss`)
- Pricing: https://frontegg.com/pricing
- Blog: https://frontegg.com/blog
- GitHub org: https://github.com/frontegg

## Regional gateways

| Region | Base URL |
|---|---|
| EU | `https://api.frontegg.com` |
| US | `https://api.us.frontegg.com` |
| AU | `https://api.au.frontegg.com` |
| CA | `https://api.ca.frontegg.com` |

Authentication is JWT Bearer. Management API callers exchange a Client ID + API Key at `/auth/vendor` for an environment-scoped token; user-facing flows use the Authentication API to obtain user-scoped tokens.

## APIs covered

| API | Base path | Operations | Schemas |
|---|---|---:|---:|
| Authentication and Identity Management | `/identity` | 232 | 305 |
| Entitlements | `/entitlements` | 29 | 52 |
| Single Sign-On (Team) | `/team` | 20 | 13 |
| Account Management (Tenants) | `/tenants` | 18 | 11 |
| Multi-Apps (Applications) | `/applications` | 13 | 14 |
| Audits | `/audits` | 7 | 6 |
| SCIM Provisioning | `/directory` | 2 | 4 |
| Entitlements Agent (PDP) | `localhost:8181` | 3 | 6 |
| Environment Authentication | `/auth/vendor` | 1 | 2 |

The combined spec at `openapi/frontegg-combined-openapi.yml` bundles all of the above.

## Artifacts

- `apis.yml` — API Evangelist APIs.yml 0.19 index of every Frontegg API surface, common properties, SDKs, and tools.
- `openapi/` — 10 OpenAPI 3.0 specifications (9 per-service + 1 combined), summaries title-cased.
- `rules/` — 9 Spectral rulesets enforcing Frontegg conventions (title-case summaries, regional servers, JWT bearer, required 2xx, etc.).
- `capabilities/` — 10 Naftiko capability files: 9 per-API shared capabilities plus `frontegg-b2b-onboarding.yaml`, a composed workflow that orchestrates vendor auth → tenant creation → admin invite → SSO/SCIM setup → entitlement assignment.
- `json-schema/` — 15 JSON Schema files for core Frontegg entities extracted from the OpenAPI components.
- `json-structure/` — 11 JSON Structure documents for User, Tenant, Role, Permission, SSO config, SCIM config, Entitlement, Plan, Application, Audit Event, and Vendor Token.
- `json-ld/frontegg-context.jsonld` — JSON-LD 1.1 context mapping Frontegg's domain types onto schema.org and a Frontegg-namespaced vocabulary.
- `examples/` — 17 example payloads covering user, tenant, login, vendor auth, SSO/SCIM config, entitlement check, plan, application, audit event, MFA enrollment, role, permission, invite, and feature flag.
- `vocabulary/frontegg-vocabulary.yml` — Glossary of Frontegg-specific terms (Tenant, Sub-Tenant, Vendor Token, PDP, AgentLink, Harmor, MAU, M2M, etc.).
- `plans/frontegg-plans-pricing.yml` — API Commons Plans 0.1 capture of the Pay as you go and Enterprise tiers.
- `rate-limits/frontegg-rate-limits.yml` — API Commons Rate Limits 0.1 capture of authentication, management, SCIM, and entitlement-check limits (calibrated; confirm with Frontegg support for production).
- `finops/frontegg-finops.yml` — FOCUS 1.3-aligned FinOps surface with MAU, enterprise-connection, environment, M2M-token, and organization meters.

## SDKs and tools

Frontegg publishes SDKs across frontend, mobile, backend, and infrastructure stacks. The full list lives in `apis.yml` under `common:`. Highlights:

- **Frontend:** React, Next.js, Angular, Vue, Vanilla JS
- **Mobile:** iOS Swift, Android Kotlin, Flutter, React Native, Ionic Capacitor
- **Backend:** Node.js (`nodejs-sdk`), Python (`python-sdk`), Python Flask, Java Entitlements
- **IaC:** `terraform-provider-frontegg`
- **AI / tools:** `frontegg-mcp-server`, `harmor` (data masking)

## Plans

Per https://frontegg.com/pricing:

- **Pay as you go (free):** 7,500 MAU included, 5 Enterprise Connections (SSO/SCIM), unlimited organizations, custom domain, hosted login, full CIAM feature set.
- **Enterprise (custom):** multiple environments, advanced fraud protection, 99.99% uptime SLA, premium support, add-ons.

## Status

`status.frontegg.com` tracks Authentication APIs, Management APIs, and the Management Portal across five regions (EU, US, Australia, Canada, UK). Atom and RSS feeds are published at `/history.atom` and `/history.rss`.

## Notes and absences

- Frontegg publishes individual OpenAPI documents per service plus a combined bundle at `apis-combined.json` / `combined.json` in `github.com/frontegg/openapi-public` — refreshed as of v2.1.0 (Dec 4, 2025).
- The blog has no documented RSS feed surfaced on the landing page.
- Rate-limit numbers are not publicly tabulated; the values in `rate-limits/` are calibrated estimates and should be reconciled with Frontegg support.
- The `agen.co` AgentLink product line (announced Nov 2025) is referenced on the homepage but its public APIs are not yet in the OpenAPI repo.

## Generated by

API Evangelist pipeline run on 2026-05-22. Source: https://github.com/api-evangelist/frontegg.
