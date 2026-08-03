# Ambassador (ambassador)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ambassador is a Kubernetes-native API Gateway built on Envoy Proxy, providing routing, load balancing, authentication, and observability for microservices.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ambassador/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ambassador/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- API Development
- Gateways
- Ingress
- Kubernetes
- Mock Servers
- Mocks
- Platform
- Testing

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Ambassador

Ambassador offers a suite of products designed to deliver API developer experiences that fuel innovation. These products, Blackbird API Development Platform, Edge Stack API Gateway, and Telepresence, accelerate development, expedite testing, and optimize the delivery of API resources.

- **Human URL:** [https://www.getambassador.io/](https://www.getambassador.io/)

#### Tags

- Gateways
- Mocking
- Testing

#### Properties

- [Documentation](https://www.getambassador.io/)
- [Postman Collection](collections/ambassador.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambassador.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ambassador Edge Stack API Gateway

Ambassador Edge Stack is a Kubernetes-native API gateway built on Envoy Proxy that provides routing, load balancing, authentication, rate limiting, and observability for microservices. It supports custom resource definitions (CRDs) including Mapping, Host, TLSContext, and RateLimit for declarative configuration.

- **Human URL:** [https://www.getambassador.io/products/edge-stack/api-gateway](https://www.getambassador.io/products/edge-stack/api-gateway)

#### Tags

- API Management
- Envoy
- Gateways
- Ingress
- Kubernetes

#### Properties

- [Documentation](https://www.getambassador.io/products/edge-stack/api-gateway)
- [Getting Started](https://www.getambassador.io/docs/edge-stack/latest/tutorials/getting-started/)
- [Documentation](https://www.getambassador.io/docs/edge-stack/latest/topics/install/)
- [Documentation](https://www.getambassador.io/docs/edge-stack/latest/topics/install/helm/)
- [Documentation](https://www.getambassador.io/docs/edge-stack/latest/topics/using/intro-mappings)
- [Documentation](https://www.getambassador.io/docs/edge-stack/latest/topics/running/host-crd)
- [Documentation](https://www.getambassador.io/docs/edge-stack/latest/topics/using/rate-limits)
- [Documentation](https://www.getambassador.io/docs/edge-stack/latest/topics/using/filters/oauth2)
- [Documentation](https://www.getambassador.io/docs/edge-stack/latest/topics/using/filters/apikeys)
- [Documentation](https://www.getambassador.io/docs/edge-stack/latest/topics/using/gateway-api)
- [Documentation](https://www.getambassador.io/docs/edge-stack/latest/about/changes-2.x)
- [Getting Started](https://www.getambassador.io/docs/edge-stack/latest/tutorials/quickstart-demo)
- [GitHub Repository](https://github.com/datawire/edge-stack)
- [OpenAPI](openapi/ambassador-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ambassador.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambassador.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Emissary-Ingress

Emissary-Ingress is an open-source, Kubernetes-native API gateway built on Envoy Proxy and a CNCF incubating project, formerly known as Ambassador API Gateway. It uses custom resource definitions (CRDs) including Mapping, Host, Listener, and TLSContext for declarative edge management.

- **Human URL:** [https://www.getambassador.io/docs/emissary](https://www.getambassador.io/docs/emissary)

#### Tags

- CNCF
- Envoy
- Gateways
- Ingress
- Kubernetes
- Open Source

#### Properties

- [Documentation](https://www.getambassador.io/docs/emissary)
- [Documentation](https://emissary-ingress.dev/)
- [Getting Started](https://www.getambassador.io/docs/emissary/latest/tutorials/quickstart-demo)
- [GitHub Repository](https://github.com/emissary-ingress/emissary)
- [Changelog](https://github.com/emissary-ingress/emissary/blob/master/CHANGELOG.md)
- [Postman Collection](collections/ambassador.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambassador.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ambassador Telepresence RESTful API

Telepresence provides a RESTful API server that runs on the local host, both on the local workstation and in a pod that contains a traffic-agent. The API includes healthz, consume-here, and intercept-info endpoints for managing service intercepts in Kubernetes development environments.

- **Human URL:** [https://www.getambassador.io/docs/telepresence/latest/reference/restapi](https://www.getambassador.io/docs/telepresence/latest/reference/restapi)

#### Tags

- Debugging
- Development
- Intercepts
- Kubernetes

#### Properties

- [Documentation](https://www.getambassador.io/docs/telepresence/latest/reference/restapi)
- [Getting Started](https://www.getambassador.io/docs/telepresence-oss/latest/quick-start)
- [Documentation](https://www.getambassador.io/docs/telepresence/latest/howtos/intercepts)
- [Documentation](https://www.getambassador.io/docs/telepresence/latest/concepts/intercepts)
- [Documentation](https://www.getambassador.io/docs/telepresence/latest/reference/config)
- [Documentation](https://www.getambassador.io/products/telepresence)
- [Postman Collection](collections/ambassador.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambassador.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ambassador Blackbird API Development Platform

Blackbird is an API development platform that helps developers design, build, test, and manage APIs with AI-powered code generation, mocking, and production-like test environments. It supports OpenAPI specifications and provides integrated debugging tools.

- **Human URL:** [https://www.getambassador.io/products/blackbird/api-development](https://www.getambassador.io/products/blackbird/api-development)

#### Tags

- API Development
- Code Generation
- Mocking
- OpenAPI
- Testing

#### Properties

- [Documentation](https://www.getambassador.io/products/blackbird/api-development)
- [Documentation](https://www.getambassador.io/docs/blackbird)
- [Getting Started](https://www.getambassador.io/docs/blackbird/latest/install/quickstart)
- [Getting Started](https://www.getambassador.io/docs/blackbird/latest/guides/api/quickstart)
- [Getting Started](https://www.getambassador.io/docs/blackbird/latest/guides/code/quickstart)
- [Getting Started](https://www.getambassador.io/docs/blackbird/latest/guides/deployments/quickstart)
- [Release Notes](https://www.getambassador.io/docs/blackbird/latest/release-notes)
- [Documentation](https://www.getambassador.io/docs/blackbird/latest/reference/mcp)
- [Postman Collection](collections/ambassador.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambassador.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ambassador Edge Stack Developer Portal

The Ambassador Edge Stack Developer Portal automatically detects and publishes API documentation, serving as a single point of reference for all microservice APIs. It supports Swagger and OpenAPI V3 specifications and provides a fully customizable portal for internal and external developer onboarding.

- **Human URL:** [https://www.getambassador.io/docs/edge-stack/latest/tutorials/dev-portal-tutorial](https://www.getambassador.io/docs/edge-stack/latest/tutorials/dev-portal-tutorial)

#### Tags

- API Catalog
- Developer Portal
- Documentation
- OpenAPI

#### Properties

- [Getting Started](https://www.getambassador.io/docs/edge-stack/latest/tutorials/dev-portal-tutorial)
- [Documentation](https://www.getambassador.io/docs/latest/topics/using/dev-portal/)
- [Documentation](https://www.getambassador.io/products/edge-stack/api-gateway/developer-portal)
- [Postman Collection](collections/ambassador.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambassador.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Customers](https://www.getambassador.io/case-studies)
- [Pricing](https://www.getambassador.io/pricing)
- [Blog](https://www.getambassador.io/blog)
- [F A Q](https://www.getambassador.io/faq)
- [Documentation](https://www.getambassador.io/docs)
- [Support](https://www.getambassador.io/support)
- [Partners](https://www.getambassador.io/company/partnerships)
- [Getting Started](https://www.getambassador.io/docs/edge-stack/latest/tutorials/getting-started/)
- [GitHub Repository](https://github.com/emissary-ingress/emissary)
- [Changelog](https://github.com/emissary-ingress/emissary/blob/master/CHANGELOG.md)
- [Status Page](https://status.datawire.io/)
- [Authentication](https://www.getambassador.io/products/edge-stack/api-gateway/security-authentication)
- [Rate Limits](https://www.getambassador.io/docs/edge-stack/latest/howtos/rate-limiting-tutorial)
- [X (Twitter)](https://x.com/ambassadorlabs)
- [LinkedIn](https://www.linkedin.com/company/ambassadorlabs)
- [Sign Up](https://app.getambassador.io/)
- [GitHub Repository](https://github.com/datawire/ambassador-docs)
- [GitHub Organization](https://github.com/datawire)
- [JSON-LD](json-ld/ambassador-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/ambassador-mapping-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**Email:** support@datawire.io
**URL:** https://www.getambassador.io
