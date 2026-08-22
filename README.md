# Frontegg (frontegg)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Frontegg is a customer identity and access management (CIAM) platform for B2B SaaS. It provides self-serve authentication,
multi-tenancy, role-based access control, single sign-on, SCIM provisioning, entitlements, and an admin portal that ships
with the product. Frontegg publishes OpenAPI specifications for its Authentication and Identity, Account Management,
Single Sign-On, SCIM Provisioning, Applications, Audits, Entitlements, Entitlements Agent (PDP), and Environment
Authentication APIs, all served from regional gateway endpoints (api.frontegg.com, api.us.frontegg.com, api.au.frontegg.com,
api.ca.frontegg.com).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/frontegg/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/frontegg/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Authentication
- Authorization
- Identity Management
- CIAM
- B2B SaaS
- Multi-Tenancy
- RBAC
- SSO
- SCIM
- Entitlements
- OAuth
- OpenID Connect

## Timestamps

- **Created:** 2026-05-22
- **Modified:** 2026-05-30

## APIs

### Frontegg Authentication and Identity Management API

The Frontegg Authentication and Identity Management API handles login, registration, MFA, passwordless flows, social
logins, sessions, passwords, passkeys, OAuth, OIDC, JWT, user management, roles, permissions, groups, and tenant
membership. With 232 documented operations across 305 schemas, this is the core of the Frontegg CIAM platform.

- **Human URL:** [https://developers.frontegg.com/ciam/api/identity](https://developers.frontegg.com/ciam/api/identity)
- **Base URL:** `https://api.frontegg.com/identity`

#### Tags

- Authentication
- Identity
- User Management
- MFA
- Passwordless
- OAuth
- OpenID Connect
- JWT
- Sessions

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/api/identity)
- [API Reference](https://developers.frontegg.com/ciam/api/identity)
- [OpenAPI](openapi/frontegg-identity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/frontegg-identity-rules.yml)

### Frontegg Account Management API

The Frontegg Account Management (Tenants) API manages B2B accounts, tenant hierarchies, sub-accounts, tenant metadata,
invitations, and tenant-scoped configuration. Multi-tenancy is a core Frontegg concept and this API is how callers
create and manage the tenant graph.

- **Human URL:** [https://developers.frontegg.com/ciam/api/tenants](https://developers.frontegg.com/ciam/api/tenants)
- **Base URL:** `https://api.frontegg.com/tenants`

#### Tags

- Tenants
- Accounts
- Multi-Tenancy
- B2B

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/api/tenants)
- [OpenAPI](openapi/frontegg-tenants-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-tenants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-tenants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/frontegg-tenants-rules.yml)

### Frontegg Single Sign-On API

The Frontegg Single Sign-On (Team) API manages SAML and OIDC SSO configurations, IdP metadata, JIT provisioning,
enterprise connections, and domain claims. Frontegg ships with 5 Enterprise Connections included on the free Pay
As You Go tier.

- **Human URL:** [https://developers.frontegg.com/ciam/api/team](https://developers.frontegg.com/ciam/api/team)
- **Base URL:** `https://api.frontegg.com/team`

#### Tags

- SSO
- SAML
- OIDC
- Enterprise

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/api/team)
- [OpenAPI](openapi/frontegg-sso-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-sso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-sso.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/frontegg-sso-rules.yml)

### Frontegg SCIM Provisioning API

The Frontegg SCIM 2.0 Provisioning API implements directory provisioning for users and groups from external identity
providers such as Okta, Azure AD, and Google Workspace.

- **Human URL:** [https://developers.frontegg.com/ciam/api/scim](https://developers.frontegg.com/ciam/api/scim)
- **Base URL:** `https://api.frontegg.com/directory`

#### Tags

- SCIM
- Provisioning
- Directory
- Identity

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/api/scim)
- [OpenAPI](openapi/frontegg-scim-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-scim.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-scim.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/frontegg-scim-rules.yml)

### Frontegg Entitlements API

The Frontegg Entitlements API manages feature flags, plans, subscriptions, packages, bundles, and entitlements that
determine what users and tenants are allowed to do. 29 operations across 52 schemas govern entitlement decisions in
the CIAM platform.

- **Human URL:** [https://developers.frontegg.com/ciam/api/entitlements](https://developers.frontegg.com/ciam/api/entitlements)
- **Base URL:** `https://api.frontegg.com/entitlements`

#### Tags

- Entitlements
- Feature Flags
- Authorization
- Plans
- Subscriptions

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/api/entitlements)
- [OpenAPI](openapi/frontegg-entitlements-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-entitlements.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-entitlements.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/frontegg-entitlements-rules.yml)

### Frontegg Entitlements Agent (PDP)

The Frontegg Entitlements Agent is a Policy Decision Point (PDP) that runs locally inside customer infrastructure to
evaluate entitlements with millisecond latency. Default listen port 8181. Java and Node.js bindings ship as separate
SDKs.

- **Human URL:** [https://developers.frontegg.com/ciam/api/agent](https://developers.frontegg.com/ciam/api/agent)
- **Base URL:** `http://localhost:8181`

#### Tags

- PDP
- Policy Decision Point
- Entitlements
- Authorization
- Sidecar

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/api/agent)
- [OpenAPI](openapi/frontegg-entitlements-agent-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-entitlements-agent.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-entitlements-agent.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/frontegg-entitlements-agent-rules.yml)

### Frontegg Multi-Apps API

The Frontegg Applications (Multi-Apps) API manages multiple application surfaces under a single Frontegg environment,
each with its own login experience, integrations, and tenant scope. Useful for portfolio SaaS vendors.

- **Human URL:** [https://developers.frontegg.com/ciam/api/applications](https://developers.frontegg.com/ciam/api/applications)
- **Base URL:** `https://api.frontegg.com/applications`

#### Tags

- Applications
- Multi-App
- Tenant Scoping

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/api/applications)
- [OpenAPI](openapi/frontegg-applications-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/frontegg-applications-rules.yml)

### Frontegg Audits API

The Frontegg Audits API exposes the audit log surface for compliance, SOC 2, and security incident response. Events
are streamed and queryable by tenant.

- **Human URL:** [https://developers.frontegg.com/ciam/api/audits](https://developers.frontegg.com/ciam/api/audits)
- **Base URL:** `https://api.frontegg.com/audits`

#### Tags

- Audits
- Logging
- Compliance
- Security

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/api/audits)
- [OpenAPI](openapi/frontegg-audits-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-audits.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-audits.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/frontegg-audits-rules.yml)

### Frontegg Environment Authentication API

The Frontegg Environment Authentication endpoint exchanges a Client ID and API Key for an environment-scoped JWT,
which is then used as the Bearer token for Management APIs. Single operation at /auth/vendor.

- **Human URL:** [https://developers.frontegg.com/ciam/api/overview](https://developers.frontegg.com/ciam/api/overview)
- **Base URL:** `https://api.frontegg.com/auth/vendor`

#### Tags

- Authentication
- Vendor
- Environment
- JWT

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/api/overview)
- [OpenAPI](openapi/frontegg-env-auth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-env-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-env-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Frontegg Combined API

The combined OpenAPI specification bundles all Frontegg public services (Identity, Tenants, SSO, SCIM, Entitlements,
Applications, Audits, and Environment Authentication) into a single document for end-to-end client generation.

- **Human URL:** [https://github.com/frontegg/openapi-public](https://github.com/frontegg/openapi-public)
- **Base URL:** `https://api.frontegg.com`

#### Tags

- Combined
- Aggregated
- CIAM

#### Properties

- [Source Code](https://github.com/frontegg/openapi-public)
- [OpenAPI](openapi/frontegg-combined-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/frontegg-combined.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-combined.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Frontegg Webhooks

AsyncAPI 2.6 description of Frontegg's outbound webhook surface. Covers authentication, MFA, user lifecycle, tenant
lifecycle, group, application, plan, API token, account security, and SCIM provisioning events. Frontegg signs each
delivery with an x-webhook-secret header and treats any 2XX HTTP response as a successful delivery.

- **Human URL:** [https://developers.frontegg.com/ciam/guides/integrations/webhooks](https://developers.frontegg.com/ciam/guides/integrations/webhooks)
- **Base URL:** `https://api.frontegg.com`

#### Tags

- Webhooks
- AsyncAPI
- Events
- Authentication
- User Lifecycle
- Tenant Lifecycle
- MFA
- SCIM

#### Properties

- [Documentation](https://developers.frontegg.com/ciam/guides/integrations/webhooks)
- [AsyncAPI](asyncapi/frontegg-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/frontegg-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/frontegg-audits.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-audits.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/frontegg-combined.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-combined.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/frontegg-entitlements-agent.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-entitlements-agent.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/frontegg-entitlements.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-entitlements.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/frontegg-env-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-env-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/frontegg-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/frontegg-scim.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-scim.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/frontegg-sso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-sso.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/frontegg-tenants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/frontegg-tenants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://frontegg.com)
- [Sign Up](https://frontegg-prod.us.frontegg.com/oauth/account/sign-up)
- [Documentation](https://developers.frontegg.com)
- [API Reference](https://developers.frontegg.com/ciam/api/overview)
- [Getting Started](https://developers.frontegg.com/guides/getting-started/home)
- [Pricing](https://frontegg.com/pricing)
- [Blog](https://frontegg.com/blog)
- [Status Page](https://status.frontegg.com)
- [Status Atom](https://status.frontegg.com/history.atom)
- [Status R S S](https://status.frontegg.com/history.rss)
- [Git Hub](https://github.com/frontegg)
- [Open A P I Repository](https://github.com/frontegg/openapi-public)
- [SDK](https://github.com/frontegg/frontegg-react)
- [SDK](https://github.com/frontegg/frontegg-nextjs)
- [SDK](https://github.com/frontegg/frontegg-angular)
- [SDK](https://github.com/frontegg/frontegg-vue)
- [SDK](https://github.com/frontegg/nodejs-sdk)
- [SDK](https://github.com/frontegg/python-sdk)
- [SDK](https://github.com/frontegg/frontegg-flutter)
- [SDK](https://github.com/frontegg/frontegg-ios-swift)
- [SDK](https://github.com/frontegg/frontegg-android-kotlin)
- [SDK](https://github.com/frontegg/frontegg-ionic-capacitor)
- [Tool](https://github.com/frontegg/terraform-provider-frontegg)
- [Tool](https://github.com/frontegg/frontegg-mcp-server)
- [Tool](https://github.com/frontegg/harmor)
- [Plans](plans/frontegg-plans-pricing.yml)
- [Rate Limits](rate-limits/frontegg-rate-limits.yml)
- [Fin Ops](finops/frontegg-finops.yml)
- [Vocabulary](vocabulary/frontegg-vocabulary.yml)
- [J S O N L D Context](json-ld/frontegg-context.jsonld)
- [L L Ms Txt](https://developers.frontegg.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
