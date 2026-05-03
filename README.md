# Symphony

Symphony is a secure collaboration platform designed for professional teams, particularly in financial services. It provides end-to-end encrypted messaging, voice, video, and workflow automation for regulated industries. The Symphony developer platform enables bot automation, workflow integrations, and extension apps through a comprehensive REST API suite.

## APIs

| API | Description |
|---|---|
| [Symphony Pod API](https://docs.developers.symphony.com/bots/overview-of-rest-api) | Core platform services: users, rooms, streams, connections, presence, certificates |
| [Symphony Agent API](https://docs.developers.symphony.com/bots/overview-of-rest-api/agent-api) | Message encryption/decryption for bots, datafeed, signals, DLP |
| [Symphony Authenticator API](https://docs.developers.symphony.com/bots/authentication) | Bot authentication via mutual TLS certificate |
| [Symphony Login API](https://docs.developers.symphony.com/bots/authentication/rsa-authentication) | RSA public key authentication and OAuth2 JWT token exchange |
| [Symphony Profile Manager API](https://developers.symphony.com/) | User profile and group management microservice |
| [Symphony Community Connect API](https://docs.developers.symphony.com/symphony-rest-api/connect-api) | Cross-company onboarding and tenant lookup |

## OpenAPI Specifications

| Spec | File |
|---|---|
| Agent API | [openapi/agent-openapi-original.yml](openapi/agent-openapi-original.yml) |
| Authenticator API | [openapi/authenticator-openapi-original.yml](openapi/authenticator-openapi-original.yml) |
| Community Connect API | [openapi/community-connect-openapi-original.yml](openapi/community-connect-openapi-original.yml) |
| Login API | [openapi/login-openapi-original.yml](openapi/login-openapi-original.yml) |
| Profile Manager API | [openapi/profile-manager-openapi-original.yml](openapi/profile-manager-openapi-original.yml) |
| Pod API | [openapi/symphony-pod-api-openapi.yml](openapi/symphony-pod-api-openapi.yml) |

## Capabilities

### Shared Per-API Definitions

| Capability | Description |
|---|---|
| [Agent API](capabilities/shared/agent-api.yaml) | Message operations, datafeed, signals, DLP |
| [Pod API](capabilities/shared/pod-api.yaml) | Users, rooms, streams, connections |
| [Login API](capabilities/shared/login-api.yaml) | RSA authentication and JWT token exchange |

### Workflow Capabilities

| Workflow | APIs | Description |
|---|---|---|
| [Bot Messaging](capabilities/bot-messaging.yaml) | Agent + Pod + Login | Full bot automation: auth, messaging, rooms, real-time events, signals |

## Artifacts

| Type | Resource |
|---|---|
| Spectral Rules | [rules/symphony-rules.yml](rules/symphony-rules.yml) |
| JSON Schema - Message | [json-schema/symphony-message-schema.json](json-schema/symphony-message-schema.json) |
| JSON Schema - Room | [json-schema/symphony-room-schema.json](json-schema/symphony-room-schema.json) |
| JSON Structure - Message | [json-structure/symphony-message-structure.json](json-structure/symphony-message-structure.json) |
| JSON-LD Context | [json-ld/symphony-context.jsonld](json-ld/symphony-context.jsonld) |
| Example - Post Message | [examples/symphony-post-message-example.json](examples/symphony-post-message-example.json) |
| Example - Create Room | [examples/symphony-create-room-example.json](examples/symphony-create-room-example.json) |
| Vocabulary | [vocabulary/symphony-vocabulary.yml](vocabulary/symphony-vocabulary.yml) |

## Links

- **Website**: https://symphony.com
- **Developer Documentation**: https://docs.developers.symphony.com
- **API Reference**: https://rest-api.symphony.com
- **Developer Center**: https://symphony.com/support/developers/
- **GitHub (FINOS)**: https://github.com/finos/symphony-api-spec
- **GitHub (Platform Solutions)**: https://github.com/SymphonyPlatformSolutions
- **Authentication Guide**: https://docs.developers.symphony.com/bots/authentication
- **BDK 2.0 SDK**: https://docs.developers.symphony.com/developer-tools/developer-tools/bdk-2.0

## Maintainers

**API Evangelist** | info@apievangelist.com
