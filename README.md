# Symphony (symphony)

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
