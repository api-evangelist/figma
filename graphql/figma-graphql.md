# Figma GraphQL

## Description

Figma does not offer a native public GraphQL API. The Figma platform exposes all programmatic access through a comprehensive REST API available at `https://api.figma.com/v1/`. The REST API covers files, nodes, images, comments, teams, projects, components, styles, variables, webhooks, activity logs, payments, dev resources, and library analytics.

This directory contains a **conceptual GraphQL schema** derived from the Figma REST API surface. The schema is useful for:

- GraphQL tooling and code generation workflows
- Federated graph enrichment and catalog registration
- Wrapping Figma REST calls behind a GraphQL gateway (e.g., Apollo Server, Hasura, StepZen)
- Developer education and API modeling

## Native GraphQL

**None.** Figma has not announced a public GraphQL endpoint as of June 2026.

## Endpoint (if wrapped)

If you build a GraphQL gateway over the Figma REST API, a typical endpoint would be:

```
POST https://<your-gateway>/graphql
```

Authentication would proxy the same mechanisms Figma REST uses:

- Personal Access Token: `X-Figma-Token: <token>`
- OAuth 2.0 Bearer: `Authorization: Bearer <access_token>`

## Docs

- REST API Reference: https://developers.figma.com/docs/rest-api/
- Authentication: https://developers.figma.com/docs/rest-api/authentication/
- Changelog: https://developers.figma.com/docs/rest-api/changelog/
- Rate Limits: https://developers.figma.com/docs/rest-api/rate-limits/
- OpenAPI Spec: https://github.com/figma/rest-api-spec

## Schema

See `figma-schema.graphql` for a comprehensive SDL derived from the Figma REST API type system.
