# Frontegg (frontegg)

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
