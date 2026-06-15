# Microsoft Copilot (microsoft-copilot)

Microsoft Copilot is an AI-powered assistant that helps users with productivity tasks, content generation, and information retrieval across Microsoft 365 applications and services.

**APIs.json:** [https://copilot.microsoft.com](https://copilot.microsoft.com)

## Scope

- **Access:** 3rd-Party

## Tags

- Agents
- AI Assistant
- Artificial Intelligence
- Chatbot
- Copilot
- Extensibility
- Generative AI
- Microsoft 365
- Productivity

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Microsoft Copilot API

API for integrating Microsoft Copilot capabilities into applications.

- **Human URL:** [https://learn.microsoft.com/en-us/copilot/](https://learn.microsoft.com/en-us/copilot/)
- **Base URL:** `https://api.copilot.microsoft.com`

#### Tags

- AI
- Chat
- Completion

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/copilot/overview)
- [OpenAPI](https://api.copilot.microsoft.com/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/copilot/authentication)
- [Getting Started](https://learn.microsoft.com/en-us/copilot/get-started)
- [Postman Collection](collections/microsoft-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph API (Copilot Integration)

Microsoft Graph API endpoints for accessing Copilot features within Microsoft 365, including the Copilot namespace with retrieval, chat, search, and meeting insights capabilities.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/overview](https://learn.microsoft.com/en-us/graph/overview)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Integration
- Microsoft 365
- Microsoft Graph
- Productivity

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/overview)
- [OpenAPI](https://graph.microsoft.com/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://learn.microsoft.com/en-us/graph/use-the-api)
- [Postman Collection](collections/microsoft-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft 365 Copilot APIs

REST APIs under the Microsoft Graph /copilot/ namespace that enable secure access to Microsoft 365 Copilot capabilities including retrieval, chat, and search, for use in custom applications and agents.

- **Human URL:** [https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-apis-overview](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-apis-overview)
- **Base URL:** `https://graph.microsoft.com/v1.0/copilot`

#### Tags

- AI
- Chat
- Microsoft 365
- RAG
- Retrieval
- Search

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-apis-overview)
- [Documentation](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/api/ai-services/retrieval/overview)
- [Documentation](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/api/ai-services/chat/overview)
- [SDK](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/sdks/api-libraries)
- [OpenAPI](openapi/microsoft-copilot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/microsoft-copilot-interaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-copilot-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Microsoft 365 Copilot Connectors API

API for building custom connectors that bring external data into Microsoft Graph to enhance Microsoft 365 Copilot experiences including search and retrieval augmented generation.

- **Human URL:** [https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/overview-copilot-connector](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/overview-copilot-connector)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Connectors
- External Data
- Indexing
- Microsoft Graph

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/connecting-external-content-connectors-api-overview)
- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/connectors-api-overview?view=graph-rest-1.0)
- [Getting Started](https://learn.microsoft.com/en-us/graph/custom-connector-sdk-sample-overview)
- [SDK](https://learn.microsoft.com/en-us/graph/custom-connector-sdk-overview)
- [Postman Collection](collections/microsoft-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Copilot Studio API

APIs for building, publishing, and integrating custom agents and copilots using Microsoft Copilot Studio, including Direct Line API for connecting web and custom applications.

- **Human URL:** [https://learn.microsoft.com/en-us/microsoft-copilot-studio/](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)
- **Base URL:** `https://directline.botframework.com`

#### Tags

- Agents
- Bots
- Copilot Studio
- Direct Line
- Low-Code

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)
- [Documentation](https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-api-reference?view=azure-bot-service-4.0)
- [Authentication](https://learn.microsoft.com/en-us/microsoft-copilot-studio/configure-web-security)
- [Getting Started](https://learn.microsoft.com/en-us/microsoft-copilot-studio/publication-connect-bot-to-custom-application)
- [Postman Collection](collections/microsoft-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/microsoftcopilot)
- [Getting Started](https://learn.microsoft.com/en-us/copilot/get-started)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Pricing](https://www.microsoft.com/en-us/microsoft-copilot/pricing)
- [Support](https://support.microsoft.com/copilot)
- [Blog](https://blogs.microsoft.com/blog/tag/copilot/)
- [Status Page](https://status.microsoft.com)
- [Portal](https://developer.microsoft.com/en-us/microsoft-365/copilot)
- [SDK](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/sdks/api-libraries)
- [Code Examples](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/samples)
- [Changelog](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)
- [Release Notes](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/whats-new)
- [Security](https://learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-privacy)
- [GitHub Repository](https://github.com/microsoft/CopilotStudioSamples)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
