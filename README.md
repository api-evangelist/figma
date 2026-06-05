# Figma (figma)

Figma is a collaborative interface design tool with a comprehensive REST API for accessing and manipulating design files, projects, and teams.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/figma/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/figma/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Collaboration
- Design
- Graphics
- Interfaces
- Prototypes
- Prototyping
- UI/UX

## Timestamps

- **Created:** 2023-11-22
- **Modified:** 2026-05-19

## APIs

### Figma API

Figma allows designers to create and prototype their digital experiences - together in real-time and in one place - helping them turn their ideas and visions into products, faster. Figma's mission is to make design accessible to everyone. The Figma API is one of the ways we aim to do that.

- **Human URL:** [https://www.figma.com/developers](https://www.figma.com/developers)
- **Base URL:** `https://api.figma.com`

#### Tags

- Design
- Users

#### Properties

- [OpenAPI](openapi/figma-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/figma-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/figma-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/figma-file-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-component-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-error-response-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-get-me-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/figma-get-me-response-body-structure.json)
- [JSON Structure](json-structure/figma-error-response-payload-structure.json)
- [JSON Structure](json-structure/figma-user-structure.json)
- [JSON-LD](json-ld/figma-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/)

### Figma REST API

The Figma REST API provides programmatic access to Figma files, comments, components, and related resources. It enables developers to read and interact with design data, export assets, manage comments and reactions, and query published components and styles from team libraries.

- **Human URL:** [https://developers.figma.com/docs/rest-api/](https://developers.figma.com/docs/rest-api/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Comments
- Components
- Files
- Projects
- Users

#### Properties

- [OpenAPI](openapi/figma-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-rest-get-file-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-file-nodes-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-images-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-image-fills-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-file-versions-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-comments-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-post-comment-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-reactions-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-team-components-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-file-components-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-component-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-team-component-sets-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-team-styles-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-team-projects-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-get-project-files-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-error-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-branch-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-canvas-node-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-client-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-color-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-comment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-component-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-component-set-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-document-node-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-documentation-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-frame-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-pagination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-project-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-project-file-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-published-component-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-published-component-set-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-published-style-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-reaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-style-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-success-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-rest-version-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-rest-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/)

### Figma Files API

Figma Files API provides access to design file data including document trees, nodes, images, version history, and file metadata. Read and export design data from Figma files programmatically.

- **Human URL:** [https://developers.figma.com/docs/rest-api/file-endpoints/](https://developers.figma.com/docs/rest-api/file-endpoints/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Dev Resources
- Files

#### Properties

- [OpenAPI](openapi/figma-files-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-files-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-files-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-files-get-file-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-branch-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-canvas-node-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-color-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-comment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-component-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-component-set-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-delete-dev-resource-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-dev-resource-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-document-node-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-documentation-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-error-response-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-frame-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-get-dev-resources-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-published-component-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-published-component-set-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-reaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-style-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-style-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-files-version-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-files-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/file-endpoints/)

### Figma Images API

Figma Images API provides endpoints for rendering and exporting images from Figma files in various formats including PNG, JPG, SVG, and PDF.

- **Human URL:** [https://developers.figma.com/docs/rest-api/file-endpoints/](https://developers.figma.com/docs/rest-api/file-endpoints/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Export
- Images
- Rendering

#### Properties

- [OpenAPI](openapi/figma-images-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-images-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-images-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-images-get-images-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-images-bad-request-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-images-error-response-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-images-forbidden-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-images-internal-server-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-images-not-found-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-images-too-many-requests-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-images-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/file-endpoints/)

### Figma Teams API

Figma Teams API provides endpoints for managing team-level resources including webhooks, projects, and team configuration.

- **Human URL:** [https://developers.figma.com/docs/rest-api/file-endpoints/](https://developers.figma.com/docs/rest-api/file-endpoints/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Teams
- Webhooks

#### Properties

- [OpenAPI](openapi/figma-teams-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-teams-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-teams-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-teams-get-team-webhooks-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-teams-webhook-v2-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-teams-webhook-v2-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-teams-webhook-v2-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-teams-error-response-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-teams-forbidden-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-teams-internal-server-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-teams-not-found-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-teams-too-many-requests-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-teams-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/file-endpoints/)

### Figma Projects API

Figma Projects API provides endpoints for listing team projects and retrieving project files.

- **Human URL:** [https://developers.figma.com/docs/rest-api/projects-types/](https://developers.figma.com/docs/rest-api/projects-types/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Files
- Projects

#### Properties

- [OpenAPI](openapi/figma-projects-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-projects-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-projects-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-projects-get-project-files-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-projects-project-file-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-projects-bad-request-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-projects-error-response-payload-with-err-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-projects-error-response-payload-with-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-projects-forbidden-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-projects-internal-server-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-projects-too-many-requests-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-projects-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/projects-types/)

### Figma Me API

Figma Me API provides the endpoint for retrieving information about the currently authenticated user.

- **Human URL:** [https://developers.figma.com/docs/rest-api/users-endpoints/](https://developers.figma.com/docs/rest-api/users-endpoints/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Authentication
- Users

#### Properties

- [OpenAPI](openapi/figma-me-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-me-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-me-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-me-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-me-user-with-email-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-me-error-response-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-me-forbidden-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-me-internal-server-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-me-too-many-requests-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-me-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/users-endpoints/)

### Figma Components API

Figma Components API provides access to published components, component sets, and styles from team libraries. Query component metadata, retrieve thumbnails, and access documentation links for reusable design elements.

- **Human URL:** [https://developers.figma.com/docs/rest-api/component-types/](https://developers.figma.com/docs/rest-api/component-types/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Components
- Design Systems
- Libraries

#### Properties

- [OpenAPI](openapi/figma-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-component-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Documentation](https://developers.figma.com/docs/rest-api/component-types/)

### Figma Component Sets API

Figma Component Sets API provides endpoints for retrieving published component set metadata from team libraries.

- **Human URL:** [https://developers.figma.com/docs/rest-api/component-types/](https://developers.figma.com/docs/rest-api/component-types/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Component Sets
- Design Systems

#### Properties

- [OpenAPI](openapi/figma-component-sets-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-component-sets-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-component-sets-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-component-sets-get-component-set-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-component-sets-published-component-set-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-component-sets-frame-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-component-sets-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-component-sets-error-response-payload-with-err-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-component-sets-error-response-payload-with-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-component-sets-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/component-types/)

### Figma Styles API

Figma Styles API provides endpoints for retrieving published style metadata including colors, text styles, and effects from team libraries.

- **Human URL:** [https://developers.figma.com/docs/rest-api/component-types/](https://developers.figma.com/docs/rest-api/component-types/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Design Systems
- Styles

#### Properties

- [OpenAPI](openapi/figma-styles-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-styles-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-styles-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-styles-get-style-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-published-style-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-style-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-bad-request-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-error-response-payload-with-err-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-error-response-payload-with-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-forbidden-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-internal-server-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-not-found-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-styles-too-many-requests-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-styles-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/component-types/)

### Figma Activity Logs API

Figma Activity Logs API provides endpoints for retrieving activity log events for an organization, enabling audit trail and compliance monitoring.

- **Human URL:** [https://developers.figma.com/docs/rest-api/activity-logs/](https://developers.figma.com/docs/rest-api/activity-logs/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Activity Logs
- Audit
- Compliance

#### Properties

- [OpenAPI](openapi/figma-activity-logs-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-activity-logs-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-activity-logs-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-activity-logs-get-activity-logs-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-action-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-actor-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-context-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-file-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-org-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-project-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-team-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-log-user-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-activity-logs-meta-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-activity-logs-error-response-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-activity-logs-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/activity-logs/)

### Figma Payments API

Figma Payments API provides endpoints for querying user payment information on plugins, widgets, and Community files.

- **Human URL:** [https://developers.figma.com/docs/plugins/api/figma-payments/](https://developers.figma.com/docs/plugins/api/figma-payments/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Monetization
- Payments
- Plugins

#### Properties

- [OpenAPI](openapi/figma-payments-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-payments-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-payments-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-payments-get-payments-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-payments-payment-information-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-payments-payment-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-payments-error-response-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-payments-internal-server-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-payments-too-many-requests-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-payments-unauthorized-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-payments-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/plugins/api/figma-payments/)

### Figma Dev Resources API

Figma Dev Resources API provides endpoints for creating, updating, and deleting dev resources attached to design nodes, enabling design-to-code workflows.

- **Human URL:** [https://developers.figma.com/docs/rest-api/dev-resources/](https://developers.figma.com/docs/rest-api/dev-resources/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Design to Code
- Dev Resources
- Development

#### Properties

- [OpenAPI](openapi/figma-dev-resources-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-dev-resources-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-dev-resources-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-dev-resources-create-dev-resource-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-dev-resources-create-dev-resources-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-dev-resources-dev-resource-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-dev-resources-dev-resource-create-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-dev-resources-dev-resource-update-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-dev-resources-error-response-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-dev-resources-post-dev-resources-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-dev-resources-put-dev-resources-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-dev-resources-update-dev-resource-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-dev-resources-update-dev-resources-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-dev-resources-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/dev-resources/)

### Figma Analytics API

Figma Analytics API provides endpoints for tracking component, style, and variable usage across team libraries, enabling design system adoption measurement.

- **Human URL:** [https://developers.figma.com/docs/rest-api/library-analytics-intro/](https://developers.figma.com/docs/rest-api/library-analytics-intro/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Analytics
- Design Systems
- Libraries

#### Properties

- [OpenAPI](openapi/figma-analytics-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-analytics-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-analytics-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/figma-analytics-get-library-analytics-usages-response-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-analytics-library-analytics-usages-by-component-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-analytics-library-analytics-usages-by-file-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-analytics-library-analytics-actions-by-component-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-analytics-library-analytics-actions-by-team-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-analytics-library-analytics-style-usages-by-asset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-analytics-library-analytics-style-usages-by-file-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-analytics-library-analytics-variable-usages-by-asset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-analytics-library-analytics-variable-usages-by-file-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/figma-analytics-error-response-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/figma-analytics-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Documentation](https://developers.figma.com/docs/rest-api/library-analytics-intro/)

### Figma Comments API

Figma Commenting mode allows users to leave comments directly on layers or objects on the canvas. You can use the Figma API to post comments and reactions to a Figma file, view existing comments and reactions, and access information about a comment including when it was made, by whom, and its exact location on the canvas.

- **Human URL:** [https://developers.figma.com/docs/rest-api/comments-endpoints/](https://developers.figma.com/docs/rest-api/comments-endpoints/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Annotations
- Collaboration
- Comments
- Reactions

#### Properties

- [OpenAPI](openapi/figma-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.figma.com/docs/rest-api/comments-endpoints/)

### Figma Version History API

Figma allows you to distinguish different stages or versions of a file as it evolves over time. The Version History API provides endpoints to view, track, and restore previous versions of a file, recorded in the version history.

- **Human URL:** [https://developers.figma.com/docs/rest-api/version-history-endpoints/](https://developers.figma.com/docs/rest-api/version-history-endpoints/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Files
- History
- Versions

#### Properties

- [OpenAPI](openapi/figma-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.figma.com/docs/rest-api/version-history-endpoints/)

### Figma Variables API

The Variables REST API includes endpoints for querying, creating, updating, and deleting variables. Variables store reusable values that can be applied to design properties and prototyping actions. To use this API, you must have a Full seat in an Enterprise org.

- **Human URL:** [https://developers.figma.com/docs/rest-api/variables-endpoints/](https://developers.figma.com/docs/rest-api/variables-endpoints/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Collections
- Design Tokens
- Variables

#### Properties

- [OpenAPI](openapi/figma-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.figma.com/docs/rest-api/variables-endpoints/)

### Figma Library Analytics API

The Library Analytics REST API provides six methods for tracking component, style, and variable usage. Each resource type has an actions endpoint and a usages endpoint, allowing you to get time series data about user actions and usage data for your library assets.

- **Human URL:** [https://developers.figma.com/docs/rest-api/library-analytics-endpoints/](https://developers.figma.com/docs/rest-api/library-analytics-endpoints/)
- **Base URL:** `https://api.figma.com`

#### Tags

- Analytics
- Components
- Libraries
- Styles
- Usages
- Variables

#### Properties

- [OpenAPI](openapi/figma-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/figma-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/figma-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.figma.com/docs/rest-api/library-analytics-endpoints/)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/figma)
- [Portal](https://www.figma.com/developers)
- [Authentication](https://developers.figma.com/docs/rest-api/authentication/)
- [Changelog](https://developers.figma.com/docs/rest-api/changelog/)
- [Rate Limits](https://developers.figma.com/docs/rest-api/rate-limits/)
- [OpenAPI](https://github.com/figma/rest-api-spec) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://developers.figma.com/docs/code-connect/quickstart-guide/)
- [Sign Up](https://www.figma.com/signup?cont=/developers/embed)
- [Login](https://www.figma.com/login?cont=/developers/embed)
- [Pricing](https://www.figma.com/pricing/)
- [Blog](https://www.figma.com/blog/)
- [Security](https://www.figma.com/security/)
- [Status Page](https://status.figma.com/)
- [Terms of Service](https://www.figma.com/legal/tos/)
- [Privacy Policy](https://www.figma.com/legal/privacy/)
- [Partners](https://www.figma.com/partners/)
- [Events](https://www.figma.com/events/)
- [Support](https://help.figma.com/hc/en-us/)
- [Contact](https://www.figma.com/contact/)
- [Support](https://forum.figma.com/)
- [GitHub Organization](https://github.com/figma)
- [GitHub Repository](https://github.com/figma/rest-api-spec)
- [GitHub Repository](https://github.com/figma/code-connect)
- [GitHub Repository](https://github.com/figma/plugin-typings)
- [GitHub Repository](https://github.com/figma/community-resources)
- [GitHub Repository](https://github.com/figma/mcp-server-guide)
- [Spectral Rules](rules/figma-spectral-rules.yml)
- [Vocabulary](vocabulary/figma-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://www.figma.com/partners/)
- [Agent Skill](https://github.com/figma/community-resources)
- [L L Ms Txt](https://developers.figma.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com
**Email:** support@figma.com
**URL:** https://www.figma.com
