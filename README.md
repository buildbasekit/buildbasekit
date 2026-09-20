# BuildBaseKit

### Spring Boot foundations for developers and coding agents

**Stop rebuilding backend infrastructure.**

BuildBaseKit provides modular, AI-ready Spring Boot boilerplates for authentication and file storage, with payment foundations currently planned.

[**Website**](https://buildbasekit.com/) ·
[**Boilerplates**](https://buildbasekit.com/boilerplates/) ·
[**Documentation**](https://buildbasekit.com/docs/) ·
[**Resources**](https://buildbasekit.com/resources/)

---

## Run a foundation in minutes

Released BuildBaseKit foundations are designed around the same local-first workflow: use the included Maven wrapper, start with runnable local defaults, explore the APIs in the browser, and add environment-specific configuration only when you begin adapting the project.

For example, AuthKit-Lite:

```bash
git clone https://github.com/buildbasekit/AuthKit-Lite.git
cd AuthKit-Lite
./mvnw spring-boot:run
```

Then open:

```text
http://localhost:8080/api-test
```

**Java 25 · Git · Maven wrapper included**

No separate frontend or Postman setup is required for the first API walkthrough.

[Getting started →](https://buildbasekit.com/docs/getting-started/)

---

## Core foundations

AuthKit, FiloraFS, and StripeKit make up the core BuildBaseKit product catalogue.

| Foundation | Capability | Availability |
| --- | --- | --- |
| [**AuthKit-Lite**](https://github.com/buildbasekit/AuthKit-Lite) | Spring Boot 4 authentication boilerplate with JWT, refresh tokens, role-based access, and optional WebAuthn passkeys | **Free · Open source** |
| [**AuthKit-Pro**](https://buildbasekit.com/boilerplates/authkit-pro/) | Production-focused authentication foundation with rotating refresh sessions, account lifecycle workflows, OAuth2/OIDC, passkeys, and documented security boundaries | **Available · $39 one-time** |
| [**FiloraFS-Lite**](https://github.com/buildbasekit/FiloraFS-Lite) | Focused local file upload starter with API-key access and straightforward REST APIs | **Free · Open source** |
| [**FiloraFS-Pro**](https://buildbasekit.com/boilerplates/filora-fs-pro/) | Authenticated, ownership-aware file management with LOCAL and S3-compatible storage, runtime provider administration, temporary access, thumbnails, and protected provider configuration | **Available · $29 one-time** |
| [**StripeKit-Lite**](https://buildbasekit.com/boilerplates/stripekit-lite/) | Planned Spring Boot foundation for payment workflows | **Coming soon** |
| [**StripeKit-Pro**](https://buildbasekit.com/boilerplates/stripekit-pro/) | Planned addition to the StripeKit payments foundation family | **Coming soon** |

> **StripeKit status:** product details are still being defined. Features, compatibility, pricing, and release timing have not been finalized.

[Compare all boilerplates →](https://buildbasekit.com/boilerplates/)

---

## Why BuildBaseKit?

### AI-ready context

Repository instructions and architecture files make commands, constraints, responsibilities, and verification expectations visible to developers and coding agents before implementation begins.

BuildBaseKit foundations can include:

- `AGENTS.md` — commands, scope, constraints, and verification expectations
- `ARCHITECTURE.md` — responsibilities, dependencies, and important design decisions
- `AI_RULES.md` — predictable coding rules and repository boundaries
- `AGENT_CONTRIBUTING.md` — focused contribution and review workflow

The goal is not to make AI-generated changes automatic. It is to give coding agents the same explicit repository context a developer needs.

[Explore AI-ready foundations →](https://buildbasekit.com/features/ai-ready/)

### Focused adoption

Each foundation addresses one backend capability instead of bringing an entire application with it.

BuildBaseKit provides the infrastructure starting point. Your application keeps ownership of its domain logic, business workflows, authorization decisions, deployment choices, and product features.

[Explore modular foundations →](https://buildbasekit.com/features/modular/)

### Inspectable engineering boundaries

Architecture, configuration, validation, security, tests, compatibility, known limits, and documentation stay visible before adoption.

Released foundations are built around:

- explicit architecture and product boundaries
- runnable local defaults
- external configuration for environment-specific values
- product-appropriate security and validation
- automated verification and documented test paths
- browser API testing at `/api-test`
- documented deployment responsibilities

[Inspect production-readiness standards →](https://buildbasekit.com/features/production-ready/)

---

## Production-ready does not mean deployment-free

A foundation reduces repeated infrastructure work; it does not make every application production-ready by itself.

Application teams still own product-specific decisions such as:

- domain authorization and ownership rules
- deployment and infrastructure configuration
- monitoring and alerting
- backups and recovery
- capacity planning
- application-specific security review

BuildBaseKit keeps these boundaries explicit instead of hiding them behind a “production-ready” label.

---

## Open-source foundations

### [AuthKit-Lite](https://github.com/buildbasekit/AuthKit-Lite)

Authentication APIs with password login, JWT access tokens, rotating refresh credentials, RBAC, optional WebAuthn passkeys, Flyway migrations, local H2 defaults, tests, and a browser API console.

[Product page →](https://buildbasekit.com/boilerplates/authkit-lite/) ·
[Documentation →](https://buildbasekit.com/docs/authkit/overview/)

### [FiloraFS-Lite](https://github.com/buildbasekit/FiloraFS-Lite)

Local file storage with API-key access, upload validation, file management APIs, no database dependency, automated tests, and a browser API console.

[Product page →](https://buildbasekit.com/boilerplates/filora-fs-lite/) ·
[Documentation →](https://buildbasekit.com/docs/filorafs-lite/overview/)

---

## Other projects

### [Basely](https://github.com/buildbasekit/Basely)

Java and Spring Boot Discord bot starter with structured JDA commands, events, moderation, and scheduled work.

Basely sits outside the core BuildBaseKit backend-foundation catalogue.

---

## Documentation and resources

- [Getting started](https://buildbasekit.com/docs/getting-started/)
- [Choosing a foundation](https://buildbasekit.com/docs/choosing-a-foundation/)
- [Documentation](https://buildbasekit.com/docs/)
- [AI-ready development](https://buildbasekit.com/features/ai-ready/)
- [Production readiness](https://buildbasekit.com/features/production-ready/)
- [Modular foundations](https://buildbasekit.com/features/modular/)
- [Resources](https://buildbasekit.com/resources/)
- [Blog](https://buildbasekit.com/blog/)

---

## Follow BuildBaseKit

[Website](https://buildbasekit.com/) ·
[GitHub](https://github.com/buildbasekit) ·
[X](https://x.com/buildbasekit) ·
[DEV](https://dev.to/buildbasekit)

If a foundation saves you time, consider starring its repository. It helps other Spring Boot developers discover the project.

---

**BuildBaseKit — focused Spring Boot foundations for stronger backends.**
