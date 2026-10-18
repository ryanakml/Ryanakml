# Hey, I'm Ryan 👋

Full-stack developer from Aceh, Indonesia. I build web interfaces, APIs,
and the background jobs that keep them connected.

**Main stack:** TypeScript · React · Node.js · PostgreSQL
**Currently exploring:** worker coordination and failure recovery in Go

Open to remote full-time roles, paid internships, and contract work.
[Email me](mailto:ryan@nylo.me) · [Portfolio](https://nylo.me)

---

## Both sides of the loading spinner

Personal projects with real interfaces, backend decisions you can inspect,
and plenty of edge cases.

### [FlowDesk AI](https://github.com/ryanakml/flowdesk-ai)
A WhatsApp support workspace: React inbox, Node.js API, and
PostgreSQL-backed message processing.

**Worth a look:** webhook replay handling, tenant isolation, and keeping
background work in sync with a live inbox.

`React` `TypeScript` `Node.js` `PostgreSQL` `Docker`

[Code](https://github.com/ryanakml/flowdesk-ai) ·
[Integration tests](https://github.com/ryanakml/flowdesk-ai/blob/main/apps/worker/src/vertical-slice.integration.test.ts)

### [Wabrix](https://github.com/ryanakml/wabrix)
A WhatsApp inbox with knowledge-grounded AI replies and human handoff,
built on a managed backend with edge webhook ingress.

`Next.js` `TypeScript` `Convex` `Clerk` `Cloudflare Workers`

[Code](https://github.com/ryanakml/wabrix) ·
[Live site](https://wabrix.nylo.me/)

### [Deadbolt](https://github.com/ryanakml/Deadbolt) *(in progress)*
A workflow engine exploring how work recovers when a worker disappears:
Go control plane, PostgreSQL state, and explicit worker ownership.

**Worth a look:** leases, stale-worker safety, and recovery boundaries.

`Go` `TypeScript` `PostgreSQL` `Docker`

[Code](https://github.com/ryanakml/Deadbolt) ·
[Lease tracking](https://github.com/ryanakml/Deadbolt/blob/main/internal/worker/lease.go)

---

## Sometimes I fix other people's edge cases

Selected merged contributions:

- **[OpenHands #12223](https://github.com/OpenHands/OpenHands/pull/12223)**: chat-loading skeletons and more stable conversation routing
- **[Mastra #15346](https://github.com/mastra-ai/mastra/pull/15346)**: fixed function-based tool approval handling, with regression tests
- **[Celery #10739](https://github.com/celery/celery/pull/10739)**: fixed home-directory expansion for spawned workers' working directories, with regression coverage

[See all merged PRs →](https://github.com/search?q=author%3Aryanakml+is%3Apr+is%3Amerged+-user%3Aryanakml&type=pullrequests)

---

Got a role, a useful problem, or a suspiciously reproducible bug?
**[ryan@nylo.me](mailto:ryan@nylo.me)**
