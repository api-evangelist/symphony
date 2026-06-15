# Symphony (symphony)

Symphony is a secure collaboration platform designed for professional teams, particularly in financial services. It provides end-to-end encrypted messaging, voice, video, and workflows for regulated industries. Symphony's developer platform enables bot automation, workflow integrations, and extension apps through a suite of REST APIs including the Pod API, Agent API, Authenticator API, Login API, Profile Manager API, and Community Connect API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/apis.yml)

## Tags

- Collaboration
- Communication
- Financial Services
- Messaging
- Secure Communication

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Symphony Pod API

The Symphony Pod API provides core platform services including user management, stream (room) management, content export, connection management, security certificates, and presence. Used to build tools that manage and administer Symphony for an organization.

- **Human URL:** [https://developers.symphony.com/](https://developers.symphony.com/)
- **Base URL:** `https://acme.symphony.com`

#### Tags

- Certificates
- Connections
- Messaging
- Presence
- Rooms
- Streams
- User Management
- Users

#### Properties

- [Documentation](https://docs.developers.symphony.com/bots/overview-of-rest-api)
- [OpenAPI](openapi/symphony-pod-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Symphony Agent API

The Symphony Agent API handles encryption and decryption of messages and content sent to and from bots. Provides message sending, datafeed (real-time event stream), signal management, DLP (Data Loss Prevention), and content sharing operations. Requires the on-premise Agent server to be deployed.

- **Human URL:** [https://docs.developers.symphony.com/bots/overview-of-rest-api/agent-api](https://docs.developers.symphony.com/bots/overview-of-rest-api/agent-api)
- **Base URL:** `https://acme.symphony.com`

#### Tags

- Attachment
- Bots
- Data Loss Prevention
- Datafeed
- Encryption
- Messaging
- Real-Time
- Signals
- Streams

#### Properties

- [Documentation](https://docs.developers.symphony.com/bots/overview-of-rest-api/agent-api)
- [OpenAPI](openapi/agent-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Symphony Authenticator API

The Symphony Authenticator API enables bots and on-premise processes to authenticate via mutual TLS certificate. Returns session tokens required for all subsequent API calls. Runs on both the Pod and the Key Manager, and both tokens are needed for full authentication.

- **Human URL:** [https://docs.developers.symphony.com/bots/authentication](https://docs.developers.symphony.com/bots/authentication)
- **Base URL:** `https://acme.symphony.com`

#### Tags

- Authentication
- Bots
- Certificates
- Session
- TLS

#### Properties

- [Documentation](https://docs.developers.symphony.com/bots/authentication)
- [OpenAPI](openapi/authenticator-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Symphony Login API

The Symphony Login API enables bots and applications to authenticate using RSA public/private key pairs, producing session tokens and OAuth2-compatible JWT access tokens. Supports bot authentication, extension app authentication, and delegated user context authentication.

- **Human URL:** [https://docs.developers.symphony.com/bots/authentication/rsa-authentication](https://docs.developers.symphony.com/bots/authentication/rsa-authentication)
- **Base URL:** `https://acme.symphony.com`

#### Tags

- Authentication
- Bots
- JWT
- OAuth2
- Public Key
- RSA
- Session

#### Properties

- [Documentation](https://docs.developers.symphony.com/bots/authentication/rsa-authentication)
- [OpenAPI](openapi/login-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Symphony Profile Manager API

Profile Manager is a microservice to manage user profiles and groups in Symphony. Supports group creation, membership management, and profile retrieval for enterprise directory use cases.

- **Human URL:** [https://developers.symphony.com/](https://developers.symphony.com/)
- **Base URL:** `https://acme.symphony.com/profile-manager`

#### Tags

- Directory
- Groups
- Profiles
- User Management
- Users

#### Properties

- [Documentation](https://developers.symphony.com/)
- [OpenAPI](openapi/profile-manager-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Symphony Community Connect API

The Symphony Community Connect API enables cross-company secure messaging and collaboration. Provides onboarding and tenant lookup for users joining Symphony Community Connect (formerly known as Channel Connect), enabling organizations to communicate with external partners over encrypted Symphony channels.

- **Human URL:** [https://docs.developers.symphony.com/symphony-rest-api/connect-api](https://docs.developers.symphony.com/symphony-rest-api/connect-api)
- **Base URL:** `https://acme.symphony.com`

#### Tags

- Collaboration
- Community
- Onboarding
- Tenants
- Users

#### Properties

- [Documentation](https://docs.developers.symphony.com/symphony-rest-api/connect-api)
- [OpenAPI](openapi/community-connect-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/symphonycomm)
- [Website](https://symphony.com)
- [Developer  Documentation](https://docs.developers.symphony.com)
- [API Reference](https://rest-api.symphony.com)
- [Developer  Center](https://symphony.com/support/developers/)
- [Git Hub](https://github.com/finos/symphony-api-spec)
- [GitHub Organization](https://github.com/SymphonyPlatformSolutions)
- [Authentication](https://docs.developers.symphony.com/bots/authentication)
- [Sandbox](https://developers.symphony.com/)
- [Developer  Certification](https://developers.symphony.com/)
- [SDK](https://docs.developers.symphony.com/developer-tools/developer-tools/bdk-2.0)
- [Changelog](https://docs.developers.symphony.com/admin-guide/release-notes)
- [Integrations](https://symphony.com/messaging/integrations/)
- [L L Ms Txt](https://rest-api.symphony.com/llms.txt)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
