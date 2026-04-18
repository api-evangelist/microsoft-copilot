# Microsoft Copilot (microsoft-copilot)
Microsoft Copilot is an AI-powered assistant that helps users with productivity tasks, content generation, and information retrieval across Microsoft 365 applications and services.

**URL:** [Visit APIs.json URL](https://copilot.microsoft.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Agents, AI Assistant, Artificial Intelligence, Chatbot, Copilot, Extensibility, Generative AI, Microsoft 365, Productivity

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### Microsoft Copilot API
API for integrating Microsoft Copilot capabilities into applications.

**Human URL:** [https://learn.microsoft.com/en-us/copilot/](https://learn.microsoft.com/en-us/copilot/)

#### Tags:

 - AI, Chat, Completion

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/copilot/overview)
- [OpenAPI](https://api.copilot.microsoft.com/openapi.json)
- [Authentication](https://learn.microsoft.com/en-us/copilot/authentication)
- [GettingStarted](https://learn.microsoft.com/en-us/copilot/get-started)

### Microsoft Graph API (Copilot Integration)
Microsoft Graph API endpoints for accessing Copilot features within Microsoft 365, including the Copilot namespace with retrieval, chat, search, and meeting insights capabilities.

**Human URL:** [https://learn.microsoft.com/en-us/graph/overview](https://learn.microsoft.com/en-us/graph/overview)

#### Tags:

 - Integration, Microsoft 365, Microsoft Graph, Productivity

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/overview)
- [OpenAPI](https://graph.microsoft.com/openapi.json)
- [GettingStarted](https://learn.microsoft.com/en-us/graph/use-the-api)

### Microsoft 365 Copilot APIs
REST APIs under the Microsoft Graph /copilot/ namespace that enable secure access to Microsoft 365 Copilot capabilities including retrieval, chat, and search, for use in custom applications and agents.

**Human URL:** [https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-apis-overview](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-apis-overview)

#### Tags:

 - AI, Chat, Microsoft 365, RAG, Retrieval, Search

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/copilot-apis-overview)
- [SDK](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/sdks/api-libraries)
- [OpenAPI](openapi/microsoft-copilot-openapi.yml)
- [JSONSchema](json-schema/microsoft-copilot-interaction-schema.json)
- [JSONLD](json-ld/microsoft-copilot-context.jsonld)

### Microsoft 365 Copilot Connectors API
API for building custom connectors that bring external data into Microsoft Graph to enhance Microsoft 365 Copilot experiences including search and retrieval augmented generation.

**Human URL:** [https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/overview-copilot-connector](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/overview-copilot-connector)

#### Tags:

 - Connectors, External Data, Indexing, Microsoft Graph

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/connecting-external-content-connectors-api-overview)
- [GettingStarted](https://learn.microsoft.com/en-us/graph/custom-connector-sdk-sample-overview)
- [SDK](https://learn.microsoft.com/en-us/graph/custom-connector-sdk-overview)

### Microsoft Copilot Studio API
APIs for building, publishing, and integrating custom agents and copilots using Microsoft Copilot Studio, including Direct Line API for connecting web and custom applications.

**Human URL:** [https://learn.microsoft.com/en-us/microsoft-copilot-studio/](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)

#### Tags:

 - Agents, Bots, Copilot Studio, Direct Line, Low-Code

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)
- [Authentication](https://learn.microsoft.com/en-us/microsoft-copilot-studio/configure-web-security)
- [GettingStarted](https://learn.microsoft.com/en-us/microsoft-copilot-studio/publication-connect-bot-to-custom-application)

## Common Properties

- [GettingStarted](https://learn.microsoft.com/en-us/copilot/get-started)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/)
- [TermsOfService](https://www.microsoft.com/en-us/legal/terms-of-use)
- [PrivacyPolicy](https://privacy.microsoft.com/en-us/privacystatement)
- [Pricing](https://www.microsoft.com/en-us/microsoft-copilot/pricing)
- [Support](https://support.microsoft.com/copilot)
- [Blog](https://blogs.microsoft.com/blog/tag/copilot/)
- [StatusPage](https://status.microsoft.com)
- [Portal](https://developer.microsoft.com/en-us/microsoft-365/copilot)
- [SDK](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/sdks/api-libraries)
- [CodeExamples](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/samples)
- [ChangeLog](https://learn.microsoft.com/en-us/copilot/microsoft-365/release-notes)
- [ReleaseNotes](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/whats-new)
- [Security](https://learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-privacy)
- [GitHubRepository](https://github.com/microsoft/CopilotStudioSamples)

## Features

| Name | Description |
|------|-------------|
| Retrieval API | Retrieve relevant enterprise content from Microsoft 365 using AI-powered retrieval augmented generation with permissions and sensitivity label awareness. |
| Search API | Perform semantic search across Microsoft 365 content including SharePoint, OneDrive, and Exchange with AI-enhanced ranking. |
| Chat API | Programmatically start and continue conversations with Microsoft 365 Copilot grounded in enterprise and web search data. |
| Interaction Export | Export and audit Copilot interaction history across the organization for compliance and governance purposes. |
| Change Notifications | Subscribe to real-time notifications for Copilot interactions and events across Microsoft 365. |
| Copilot Studio | Low-code platform for building custom agents, copilots, and conversational AI experiences. |
| Connectors | Bring external data into Microsoft Graph to enhance Copilot search and retrieval capabilities. |
| Extensibility | Extend Copilot with custom plugins, agents, and API integrations using declarative or code-first approaches. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise Knowledge Retrieval | Build applications that retrieve relevant enterprise content from Microsoft 365 while respecting permissions and compliance controls. |
| AI-Assisted Productivity | Integrate Copilot capabilities into line-of-business applications for document summarization, drafting, and data analysis. |
| Custom Agent Development | Create domain-specific AI agents using Copilot Studio that automate workflows and answer questions from custom data sources. |
| Compliance and Governance | Monitor and audit Copilot usage across the organization with interaction history export and change notifications. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft 365 | Deep integration with Word, Excel, PowerPoint, Outlook, Teams, and other Microsoft 365 applications. |
| Microsoft Graph | Access organizational data through the Microsoft Graph API for retrieval, search, and chat capabilities. |
| Azure Active Directory | Enterprise authentication and authorization using Azure AD with OAuth 2.0 and OIDC. |
| Power Platform | Connect Copilot with Power Automate, Power Apps, and Power BI for end-to-end workflow automation. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Microsoft Copilot APIs](openapi/microsoft-copilot-openapi.yml)

### JSON Schema

- [Microsoft Copilot Interaction Schema](json-schema/microsoft-copilot-interaction-schema.json)

### JSON-LD

- [Microsoft Copilot Context](json-ld/microsoft-copilot-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
