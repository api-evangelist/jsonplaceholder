# JSONPlaceholder (jsonplaceholder)

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

JSONPlaceholder is a free, no-auth fake REST API for prototyping, tutorials, and testing. It exposes six relational resources — posts, comments, albums, photos, todos, and users — over six standard REST routes per resource. All write operations (POST, PUT, PATCH, DELETE) are accepted and respond as if successful, but no changes are persisted. The service is built on the open-source json-server engine (also by typicode) and serves billions of requests per month with no rate limits or authentication.

**APIs.json:** [https://jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com)

## Tags

- Development
- Testing
- Prototyping
- Fake API
- Open Source
- REST

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### JSONPlaceholder REST API

Free fake REST API surface exposing six relational resources (posts, comments, albums, photos, todos, users). Supports GET / POST / PUT / PATCH / DELETE plus nested routes (e.g. /posts/1/comments) and basic query-string filtering (e.g. /comments?postId=1). Write operations are simulated — the service responds with the expected payload but does not persist changes.

- **Human URL:** [https://jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com)
- **Base URL:** `https://jsonplaceholder.typicode.com`

#### Tags

- REST
- Fake API
- Testing

#### Properties

- [Documentation](https://jsonplaceholder.typicode.com)
- [Getting Started](https://jsonplaceholder.typicode.com/guide/)
- [OpenAPI](openapi/jsonplaceholder-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jsonplaceholder.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jsonplaceholder.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/jsonplaceholder-post-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jsonplaceholder-comment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jsonplaceholder-album-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jsonplaceholder-photo-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jsonplaceholder-todo-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jsonplaceholder-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/jsonplaceholder-post-structure.json)
- [JSON Structure](json-structure/jsonplaceholder-comment-structure.json)
- [JSON Structure](json-structure/jsonplaceholder-album-structure.json)
- [JSON Structure](json-structure/jsonplaceholder-photo-structure.json)
- [JSON Structure](json-structure/jsonplaceholder-todo-structure.json)
- [JSON Structure](json-structure/jsonplaceholder-user-structure.json)
- [JSON-LD](json-ld/jsonplaceholder-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/jsonplaceholder-post-example.json)
- [Example](examples/jsonplaceholder-comment-example.json)
- [Example](examples/jsonplaceholder-album-example.json)
- [Example](examples/jsonplaceholder-photo-example.json)
- [Example](examples/jsonplaceholder-todo-example.json)
- [Example](examples/jsonplaceholder-user-example.json)

## Common Properties

- [Website](https://jsonplaceholder.typicode.com)
- [Getting Started](https://jsonplaceholder.typicode.com/guide/)
- [GitHub Repository](https://github.com/typicode/jsonplaceholder)
- [GitHub Repository](https://github.com/typicode/json-server)
- [GitHub Repository](https://github.com/typicode/lowdb)
- [GitHub Organization](https://github.com/typicode)
- [Blog](https://blog.typicode.com)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Plans](plans/jsonplaceholder-plans-pricing.yml)
- [Rate Limits](rate-limits/jsonplaceholder-rate-limits.yml)
- [Spectral Rules](rules/jsonplaceholder-rules.yml)
- [Vocabulary](vocabulary/jsonplaceholder-vocabulary.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
