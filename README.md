# Ambassador (ambassador)
Ambassador is a Kubernetes-native API Gateway built on Envoy Proxy, providing routing, load balancing, authentication, and observability for microservices.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ambassador/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Development, Gateways, Ingress, Kubernetes, Mock Servers, Mocks, Platform, Testing

## Timestamps

- **Created:** 2025-01-08 
- **Modified:** 2026-04-18 

## APIs

### Ambassador
Ambassador offers a suite of products designed to deliver API developer experiences that fuel innovation. These products, Blackbird API Development Platform, Edge Stack API Gateway, and Telepresence, accelerate development, expedite testing, and optimize the delivery of API resources.

**Human URL:** [https://www.getambassador.io/](https://www.getambassador.io/)

#### Tags:

 - Gateways, Mocking, Testing

#### Properties

- [Documentation](https://www.getambassador.io/)

### Ambassador Edge Stack API Gateway
Ambassador Edge Stack is a Kubernetes-native API gateway built on Envoy Proxy that provides routing, load balancing, authentication, rate limiting, and observability for microservices. It supports custom resource definitions (CRDs) including Mapping, Host, TLSContext, and RateLimit for declarative configuration.

**Human URL:** [https://www.getambassador.io/products/edge-stack/api-gateway](https://www.getambassador.io/products/edge-stack/api-gateway)

#### Tags:

 - API Management, Envoy, Gateways, Ingress, Kubernetes

#### Properties

- [Documentation](https://www.getambassador.io/products/edge-stack/api-gateway)
- [GettingStarted](https://www.getambassador.io/docs/edge-stack/latest/tutorials/getting-started/)
- [GitHubRepository](https://github.com/datawire/edge-stack)
- [OpenAPI](openapi/ambassador-openapi.yml)

### Emissary-Ingress
Emissary-Ingress is an open-source, Kubernetes-native API gateway built on Envoy Proxy and a CNCF incubating project, formerly known as Ambassador API Gateway. It uses custom resource definitions (CRDs) including Mapping, Host, Listener, and TLSContext for declarative edge management.

**Human URL:** [https://www.getambassador.io/docs/emissary](https://www.getambassador.io/docs/emissary)

#### Tags:

 - CNCF, Envoy, Gateways, Ingress, Kubernetes, Open Source

#### Properties

- [Documentation](https://www.getambassador.io/docs/emissary)
- [GettingStarted](https://www.getambassador.io/docs/emissary/latest/tutorials/quickstart-demo)
- [GitHubRepository](https://github.com/emissary-ingress/emissary)
- [ChangeLog](https://github.com/emissary-ingress/emissary/blob/master/CHANGELOG.md)

### Ambassador Telepresence RESTful API
Telepresence provides a RESTful API server that runs on the local host, both on the local workstation and in a pod that contains a traffic-agent. The API includes healthz, consume-here, and intercept-info endpoints for managing service intercepts in Kubernetes development environments.

**Human URL:** [https://www.getambassador.io/docs/telepresence/latest/reference/restapi](https://www.getambassador.io/docs/telepresence/latest/reference/restapi)

#### Tags:

 - Debugging, Development, Intercepts, Kubernetes

#### Properties

- [Documentation](https://www.getambassador.io/docs/telepresence/latest/reference/restapi)
- [GettingStarted](https://www.getambassador.io/docs/telepresence-oss/latest/quick-start)

### Ambassador Blackbird API Development Platform
Blackbird is an API development platform that helps developers design, build, test, and manage APIs with AI-powered code generation, mocking, and production-like test environments. It supports OpenAPI specifications and provides integrated debugging tools.

**Human URL:** [https://www.getambassador.io/products/blackbird/api-development](https://www.getambassador.io/products/blackbird/api-development)

#### Tags:

 - API Development, Code Generation, Mocking, OpenAPI, Testing

#### Properties

- [Documentation](https://www.getambassador.io/products/blackbird/api-development)
- [GettingStarted](https://www.getambassador.io/docs/blackbird/latest/install/quickstart)
- [ReleaseNotes](https://www.getambassador.io/docs/blackbird/latest/release-notes)

### Ambassador Edge Stack Developer Portal
The Ambassador Edge Stack Developer Portal automatically detects and publishes API documentation, serving as a single point of reference for all microservice APIs. It supports Swagger and OpenAPI V3 specifications and provides a fully customizable portal for internal and external developer onboarding.

**Human URL:** [https://www.getambassador.io/docs/edge-stack/latest/tutorials/dev-portal-tutorial](https://www.getambassador.io/docs/edge-stack/latest/tutorials/dev-portal-tutorial)

#### Tags:

 - API Catalog, Developer Portal, Documentation, OpenAPI

#### Properties

- [GettingStarted](https://www.getambassador.io/docs/edge-stack/latest/tutorials/dev-portal-tutorial)
- [Documentation](https://www.getambassador.io/docs/latest/topics/using/dev-portal/)

## Common Properties

- [Customers](https://www.getambassador.io/case-studies)
- [Pricing](https://www.getambassador.io/pricing)
- [Blog](https://www.getambassador.io/blog)
- [FAQ](https://www.getambassador.io/faq)
- [Documentation](https://www.getambassador.io/docs)
- [Support](https://www.getambassador.io/support)
- [Partners](https://www.getambassador.io/company/partnerships)
- [GettingStarted](https://www.getambassador.io/docs/edge-stack/latest/tutorials/getting-started/)
- [GitHubRepository](https://github.com/emissary-ingress/emissary)
- [ChangeLog](https://github.com/emissary-ingress/emissary/blob/master/CHANGELOG.md)
- [StatusPage](https://status.datawire.io/)
- [Authentication](https://www.getambassador.io/products/edge-stack/api-gateway/security-authentication)
- [RateLimits](https://www.getambassador.io/docs/edge-stack/latest/howtos/rate-limiting-tutorial)
- [X](https://x.com/ambassadorlabs)
- [LinkedIn](https://www.linkedin.com/company/ambassadorlabs)
- [SignUp](https://app.getambassador.io/)
- [GitHubOrganization](https://github.com/datawire)

## Features

| Name | Description |
|------|-------------|
| Kubernetes-Native API Gateway | Purpose-built for Kubernetes with custom resource definitions (CRDs) for declarative configuration of routing, TLS, and rate limiting. |
| Envoy Proxy Foundation | Built on Envoy Proxy for high-performance load balancing, circuit breaking, and observability at the edge. |
| Authentication and Security | Integrated OAuth2, API key, and JWT-based authentication filters to secure API endpoints without custom code. |
| Rate Limiting | Configurable rate limiting with labels and descriptors to control request throughput to backend services. |
| Developer Portal | Automatic API documentation publishing from OpenAPI/Swagger specs with customizable developer portal for onboarding. |
| Local Development with Telepresence | Intercept and debug remote Kubernetes services locally using Telepresence for fast inner-loop development. |
| API Mocking with Blackbird | AI-powered API development platform with mock servers and production-like test environments for rapid iteration. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices API Gateway | Route, secure, and observe traffic to microservices running in Kubernetes clusters. |
| API Development and Testing | Design, mock, and test APIs locally with Blackbird before deploying to Kubernetes environments. |
| Multi-Team API Management | Enable multiple teams to independently manage their API routing and configuration using Kubernetes CRDs. |
| Service Mesh Edge Gateway | Serve as the edge gateway in a service mesh architecture, handling north-south traffic with TLS termination. |
| Developer Onboarding | Provide a self-service developer portal for internal and external developers to discover and consume APIs. |

## Integrations

| Name | Description |
|------|-------------|
| Kubernetes | Native integration with Kubernetes using CRDs for Mapping, Host, TLSContext, and RateLimit resources. |
| Envoy Proxy | Built on Envoy Proxy with full access to Envoy's load balancing, circuit breaking, and observability features. |
| Helm | Install and manage Ambassador Edge Stack using Helm charts for Kubernetes deployments. |
| Prometheus and Grafana | Export metrics to Prometheus and visualize API gateway performance in Grafana dashboards. |
| Cert-Manager | Automatic TLS certificate management via cert-manager and ACME protocol integration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Ambassador Edge Stack API](openapi/ambassador-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Ambassador Edge Stack API](capabilities/shared/edge-stack.yaml) -- 26 operations for gateway resource management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Gateway Management](capabilities/gateway-management.yaml) | Edge Stack | 26 | Platform Engineer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
**FN:** Ambassador Labs (Datawire)

**Email:** support@datawire.io
