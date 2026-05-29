# JSONPlaceholder (jsonplaceholder)

JSONPlaceholder is a free, no-auth fake REST API for prototyping, tutorials, and testing. It exposes six relational resources — posts, comments, albums, photos, todos, and users — over six standard REST routes per resource. All write operations (POST, PUT, PATCH, DELETE) are accepted and respond as if successful, but no changes are persisted. The service is built on the open-source json-server engine (also by typicode) and serves billions of requests per month with no rate limits or authentication.

**URL:** [Visit APIs.json URL](https://jsonplaceholder.typicode.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags:

- Development, Testing, Prototyping, Fake API, Open Source, REST

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### JSONPlaceholder REST API

Free fake REST API surface exposing six relational resources (posts, comments, albums, photos, todos, users). Supports GET / POST / PUT / PATCH / DELETE plus nested routes (e.g. /posts/1/comments) and basic query-string filtering (e.g. /comments?postId=1). Write operations are simulated — the service responds with the expected payload but does not persist changes.

**Human URL:** [https://jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com)

#### Tags:

- REST, Fake API, Testing

#### Properties

- [Documentation](https://jsonplaceholder.typicode.com)
- [GettingStarted](https://jsonplaceholder.typicode.com/guide/)
- [OpenAPI](openapi/jsonplaceholder-openapi.yml)
- [JSONSchema — Post Schema](json-schema/jsonplaceholder-post-schema.json)
- [JSONSchema — Comment Schema](json-schema/jsonplaceholder-comment-schema.json)
- [JSONSchema — Album Schema](json-schema/jsonplaceholder-album-schema.json)
- [JSONSchema — Photo Schema](json-schema/jsonplaceholder-photo-schema.json)
- [JSONSchema — Todo Schema](json-schema/jsonplaceholder-todo-schema.json)
- [JSONSchema — User Schema](json-schema/jsonplaceholder-user-schema.json)
- [JSONStructure — Post Structure](json-structure/jsonplaceholder-post-structure.json)
- [JSONStructure — Comment Structure](json-structure/jsonplaceholder-comment-structure.json)
- [JSONStructure — Album Structure](json-structure/jsonplaceholder-album-structure.json)
- [JSONStructure — Photo Structure](json-structure/jsonplaceholder-photo-structure.json)
- [JSONStructure — Todo Structure](json-structure/jsonplaceholder-todo-structure.json)
- [JSONStructure — User Structure](json-structure/jsonplaceholder-user-structure.json)
- [JSONLD](json-ld/jsonplaceholder-context.jsonld)
- [Example — Post](examples/jsonplaceholder-post-example.json)
- [Example — Comment](examples/jsonplaceholder-comment-example.json)
- [Example — Album](examples/jsonplaceholder-album-example.json)
- [Example — Photo](examples/jsonplaceholder-photo-example.json)
- [Example — Todo](examples/jsonplaceholder-todo-example.json)
- [Example — User](examples/jsonplaceholder-user-example.json)
- [NaftikoCapability — Posts](capabilities/jsonplaceholder-posts.yaml)
- [NaftikoCapability — Comments](capabilities/jsonplaceholder-comments.yaml)
- [NaftikoCapability — Albums](capabilities/jsonplaceholder-albums.yaml)
- [NaftikoCapability — Photos](capabilities/jsonplaceholder-photos.yaml)
- [NaftikoCapability — Todos](capabilities/jsonplaceholder-todos.yaml)
- [NaftikoCapability — Users](capabilities/jsonplaceholder-users.yaml)

## Common Properties

- [Website](https://jsonplaceholder.typicode.com)
- [GettingStarted](https://jsonplaceholder.typicode.com/guide/)
- [GitHubRepository — JSONPlaceholder Source](https://github.com/typicode/jsonplaceholder)
- [GitHubRepository — json-server (Engine)](https://github.com/typicode/json-server)
- [GitHubRepository — lowdb (Storage)](https://github.com/typicode/lowdb)
- [GitHubOrganization](https://github.com/typicode)
- [Blog](https://blog.typicode.com)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [Plans](plans/jsonplaceholder-plans-pricing.yml)
- [RateLimits](rate-limits/jsonplaceholder-rate-limits.yml)
- [SpectralRules](rules/jsonplaceholder-rules.yml)
- [Vocabulary](vocabulary/jsonplaceholder-vocabulary.yml)

## Features

| Name | Description |
|------|-------------|
| Six Relational Resources | Posts, comments, albums, photos, todos, and users with realistic relationships between them (posts belong to users, comments belong to posts, etc.). |
| Full REST Surface | GET, POST, PUT, PATCH, and DELETE methods are accepted on every resource — write operations simulate success without persisting changes. |
| Nested Routes | Single-level nested access such as /posts/1/comments, /albums/1/photos, and /users/1/todos for relational queries. |
| Query Filtering | Basic query-string filtering on any resource field (e.g. /comments?postId=1, /posts?userId=1). |
| No Authentication | Open to the public — no API keys, OAuth, or signup required. Use it in tutorials, sandboxes, and frontend demos freely. |
| No Rate Limits | The service does not publish or enforce documented rate limits and routinely serves about three billion requests per month. |
| CORS Enabled | All origins are allowed, making the service usable directly from browser-based applications without a proxy. |
| HTTPS Only | Served exclusively over HTTPS for safe inclusion in modern web tutorials and demos. |

## Use Cases

| Name | Description |
|------|-------------|
| Frontend Prototyping | Wire up React, Vue, Angular, or Svelte tutorials against a real HTTP endpoint without standing up a backend. |
| API Client Testing | Exercise HTTP client libraries (fetch, axios, requests, OkHttp) against a stable public REST surface. |
| Tutorial and Courseware | Power coding tutorials, bootcamp exercises, and conference workshops that need a deterministic JSON API. |
| Mobile App Demos | Drive iOS and Android sample apps that demonstrate networking, list rendering, and CRUD flows. |
| Tooling QA | Smoke-test API generators, codegen tools, SDK builders, and OpenAPI tooling against a stable real-world API. |
| Workshop Sandboxes | Provide a no-signup HTTP API for hands-on workshops where participants cannot wait for credentials. |

## Integrations

| Name | Description |
|------|-------------|
| json-server | The open-source engine that powers JSONPlaceholder — runs the same fake REST API locally with a single command. |
| lowdb | The tiny local JSON database that json-server uses for storage; ships from the same typicode org. |
| Postman | Public collections wrap JSONPlaceholder for quick HTTP exploration and learning. |
| Hoppscotch | Frequently used as the default example endpoint in HTTP clients including Hoppscotch and Insomnia. |
| MSW (Mock Service Worker) | Often paired with MSW so frontend tests can intercept and stub JSONPlaceholder traffic deterministically. |

## Solutions

| Name | Description |
|------|-------------|
| Local Mirror via json-server | For teams that need write persistence or offline development, install json-server, point it at a local db.json, and reproduce JSONPlaceholder routes verbatim. |
| My JSON Server | typicode operates an additional service (My JSON Server) that turns any GitHub-hosted db.json into a personal hosted fake REST API. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [JSONPlaceholder REST API](openapi/jsonplaceholder-openapi.yml)

### JSON Schema

- [Album Schema](json-schema/jsonplaceholder-album-schema.json)
- [Comment Schema](json-schema/jsonplaceholder-comment-schema.json)
- [Photo Schema](json-schema/jsonplaceholder-photo-schema.json)
- [Post Schema](json-schema/jsonplaceholder-post-schema.json)
- [Todo Schema](json-schema/jsonplaceholder-todo-schema.json)
- [User Schema](json-schema/jsonplaceholder-user-schema.json)

### JSON Structure

- [Album Structure](json-structure/jsonplaceholder-album-structure.json)
- [Comment Structure](json-structure/jsonplaceholder-comment-structure.json)
- [Photo Structure](json-structure/jsonplaceholder-photo-structure.json)
- [Post Structure](json-structure/jsonplaceholder-post-structure.json)
- [Todo Structure](json-structure/jsonplaceholder-todo-structure.json)
- [User Structure](json-structure/jsonplaceholder-user-structure.json)

### JSON-LD

- [JSONPlaceholder Context](json-ld/jsonplaceholder-context.jsonld)

### Examples

- [Album Example](examples/jsonplaceholder-album-example.json)
- [Comment Example](examples/jsonplaceholder-comment-example.json)
- [Photo Example](examples/jsonplaceholder-photo-example.json)
- [Post Example](examples/jsonplaceholder-post-example.json)
- [Todo Example](examples/jsonplaceholder-todo-example.json)
- [User Example](examples/jsonplaceholder-user-example.json)

## Capabilities

Naftiko capabilities — one self-contained file per JSONPlaceholder business surface, each exposing both a REST and an MCP adapter.

### JSONPlaceholder REST API

| Workflow | Operations | File |
|----------|-----------|------|
| Posts | 7 | [capabilities/jsonplaceholder-posts.yaml](capabilities/jsonplaceholder-posts.yaml) |
| Comments | 6 | [capabilities/jsonplaceholder-comments.yaml](capabilities/jsonplaceholder-comments.yaml) |
| Albums | 7 | [capabilities/jsonplaceholder-albums.yaml](capabilities/jsonplaceholder-albums.yaml) |
| Photos | 6 | [capabilities/jsonplaceholder-photos.yaml](capabilities/jsonplaceholder-photos.yaml) |
| Todos | 6 | [capabilities/jsonplaceholder-todos.yaml](capabilities/jsonplaceholder-todos.yaml) |
| Users | 9 | [capabilities/jsonplaceholder-users.yaml](capabilities/jsonplaceholder-users.yaml) |

## Vocabulary

- [JSONPlaceholder Vocabulary](vocabulary/jsonplaceholder-vocabulary.yml) — Unified taxonomy mapping 6 resources, 7 actions, 6 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [JSONPlaceholder Rules](rules/jsonplaceholder-rules.yml) — Spectral ruleset enforcing JSONPlaceholder API conventions across 13 categories

## Plans

- [JSONPlaceholder Plans & Pricing](plans/jsonplaceholder-plans-pricing.yml) — API Commons Plans 0.1 description of the (single, free) tier

## Rate Limits

- [JSONPlaceholder Rate Limits](rate-limits/jsonplaceholder-rate-limits.yml) — API Commons Rate Limits 0.1 description of the (undocumented, best-effort) public service

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
