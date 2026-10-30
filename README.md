# Livepeer

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

Livepeer is a decentralized video infrastructure network. Independent orchestrators run GPU hardware to provide live and on-demand video transcoding services, paid for in ETH/LPT on the Livepeer protocol. Livepeer Studio is the managed gateway and developer platform sitting on top of the network, exposing a REST API at livepeer.studio/api for live streams, on- demand assets, multistream targets, transcoding jobs, sessions, playback, signing keys, AI generation (text-to-image, image-to-image, image-to-video, upscale, audio-to-text), and webhooks. Official SDKs are published for JavaScript/TypeScript, Python, Go, and Ruby, with React Player and React Broadcast components for client-side playback and ingest.

**Areas:** Video · Streaming · Transcoding · Decentralized · Web3 · Live Streaming · AI Video

## Livepeer on APIs.io

Everything profiled for Livepeer is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/livepeer/](https://apis.io/providers/livepeer/)** — or go straight to one of the APIs or properties below.

### APIs (35)

- [Livepeer Studio REST API](https://apis.io/apis/livepeer/studio/) — Primary REST API for the Livepeer Studio gateway. Resource-oriented JSON endpoints for live streams, on-demand assets, multistream targets, transcoding…
- [Livepeer Streams API](https://apis.io/apis/livepeer/streams/) — Endpoints for creating and managing live streams, ingest RTMP/WHIP URLs, profiles for adaptive bitrate transcoding, recording, and stream keys.
- [Livepeer Assets API](https://apis.io/apis/livepeer/assets/) — Endpoints for uploading, importing, transcoding, and serving on-demand video assets, including direct upload, URL import, and IPFS storage.
- [Livepeer Multistream Targets API](https://apis.io/apis/livepeer/multistream/) — Endpoints for registering and managing multistream destinations that forward an active live stream to additional RTMP/RTMPS endpoints such as YouTube,…
- [Livepeer Webhooks API](https://apis.io/apis/livepeer/webhooks/) — Webhook management endpoints plus outbound event notifications for stream lifecycle events (stream.started, stream.idle, recording.ready, asset.ready,…
- [Livepeer Transcode API](https://apis.io/apis/livepeer/transcode/) — Endpoints for one-off transcoding jobs against source files in object storage, returning a job handle and transcoded renditions.
- [Livepeer Sessions API](https://apis.io/apis/livepeer/sessions/) — Endpoints for retrieving completed live session recordings and metadata for past live streams.
- [Livepeer Playback API](https://apis.io/apis/livepeer/playback/) — Playback info endpoint returning HLS/WebRTC playback URLs and metadata for a stream or asset, plus access-control gating.
- [Livepeer Signing Keys API](https://apis.io/apis/livepeer/signing-keys/) — Endpoints for managing JWT signing keys used for playback access control and webhook signature verification.
- [Livepeer AI Generate API](https://apis.io/apis/livepeer/ai-generate/) — AI video and image generation endpoints (text-to-image, image-to-image, image-to-video, upscale, audio-to-text) routed through the Livepeer AI subnet of GPU…
- [Livepeer JavaScript/TypeScript SDK](https://apis.io/apis/livepeer/js-sdk/) — Official TypeScript/JavaScript SDK (@livepeer/ai or livepeer) for the Livepeer Studio REST API and AI endpoints.
- [Livepeer Python SDK](https://apis.io/apis/livepeer/python-sdk/) — Official Python SDK for the Livepeer Studio REST API.
- [Livepeer Go SDK](https://apis.io/apis/livepeer/go-sdk/) — Official Go SDK for the Livepeer Studio REST API.
- [Livepeer Ruby SDK](https://apis.io/apis/livepeer/ruby-sdk/) — Official Ruby SDK for the Livepeer Studio REST API.
- [Livepeer React Player Component](https://apis.io/apis/livepeer/react-player/) — React video player component for HLS/WebRTC playback of Livepeer streams and assets, with customisable controls and access-control integration.
- [Livepeer React Broadcast Component](https://apis.io/apis/livepeer/react-broadcast/) — React component for in-browser WebRTC broadcasting to a Livepeer live stream, with device selection and settings controls.
- [Livepeer Asset API](https://apis.io/apis/livepeer/livepeer-asset-api/) — Operations related to asset/vod api
- [Livepeer Generate API](https://apis.io/apis/livepeer/livepeer-generate-api/) — Operations related to AI generate api
- [Livepeer Metrics API](https://apis.io/apis/livepeer/livepeer-metrics-api/) — Operations related to metrics api
- [Livepeer Multistream API](https://apis.io/apis/livepeer/livepeer-multistream-api/) — Operations related to multistream api
- [Livepeer Playback API](https://apis.io/apis/livepeer/livepeer-playback-api/) — Operations related to playback api
- [Livepeer Room API](https://apis.io/apis/livepeer/livepeer-room-api/) — Operations related to rooms api
- [Livepeer Session API](https://apis.io/apis/livepeer/livepeer-session-api/) — Operations related to session api
- [Livepeer Stream API](https://apis.io/apis/livepeer/livepeer-stream-api/) — Operations related to livestream api
- [Livepeer Task API](https://apis.io/apis/livepeer/livepeer-task-api/) — Operations related to tasks api
- [Livepeer Transcode API](https://apis.io/apis/livepeer/livepeer-transcode-api/) — Operations related to transcode api
- [Livepeer Webhook API](https://apis.io/apis/livepeer/livepeer-webhook-api/) — Operations related to webhook api
- [Livepeer Ethereum API](https://apis.io/apis/livepeer/livepeer-ethereum-api/) — Ethereum operations and token transfers
- [Livepeer Gateway API](https://apis.io/apis/livepeer/livepeer-gateway-api/) — Gateway/broadcaster configuration
- [Livepeer Hardware API](https://apis.io/apis/livepeer/livepeer-hardware-api/) — The Hardware API from Livepeer — 2 operation(s) for hardware.
- [Livepeer Health API](https://apis.io/apis/livepeer/livepeer-health-api/) — The Health API from Livepeer — 1 operation(s) for health.
- [Livepeer Orchestrator API](https://apis.io/apis/livepeer/livepeer-orchestrator-api/) — Orchestrator configuration and management
- [Livepeer Staking API](https://apis.io/apis/livepeer/livepeer-staking-api/) — Token bonding and delegation operations
- [Livepeer Status API](https://apis.io/apis/livepeer/livepeer-status-api/) — Node status and information
- [Livepeer Access Control API](https://apis.io/apis/livepeer/livepeer-access-control-api/) — Operations related to access control/signing keys api

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (11)

Multi-step workflows that chain operations into a business task.

- [Livepeer Clip a Livestream](https://apis.io/arazzos/livepeer/livepeer-clip-livestream-workflow/)
- [Livepeer Enable Recording on a Stream](https://apis.io/arazzos/livepeer/livepeer-enable-stream-recording-workflow/)
- [Livepeer Import an Asset from a URL](https://apis.io/arazzos/livepeer/livepeer-import-asset-from-url-workflow/)
- [Livepeer Inspect a Session Recording](https://apis.io/arazzos/livepeer/livepeer-inspect-session-recording-workflow/)
- [Livepeer Provision a Live Stream](https://apis.io/arazzos/livepeer/livepeer-provision-live-stream-workflow/)
- [Livepeer Provision Multistream Restreaming](https://apis.io/arazzos/livepeer/livepeer-provision-multistream-restream-workflow/)
- [Livepeer Register a Stream Webhook](https://apis.io/arazzos/livepeer/livepeer-register-stream-webhook-workflow/)
- [Livepeer Secure a Stream with a Signing Key](https://apis.io/arazzos/livepeer/livepeer-secure-stream-signing-key-workflow/)
- [Livepeer Reuse a Standalone Multistream Target](https://apis.io/arazzos/livepeer/livepeer-standalone-multistream-target-workflow/)
- [Livepeer Run a Transcode Job](https://apis.io/arazzos/livepeer/livepeer-transcode-video-job-workflow/)
- [Livepeer Upload and Process an Asset](https://apis.io/arazzos/livepeer/livepeer-upload-and-process-asset-workflow/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Livepeer Agentic Access](https://apis.io/agentic-access/livepeer/livepeer-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [Livepeer AI — Image-to-Video](https://apis.io/schemas/livepeer/livepeer-ai-image-to-video/)
- [Livepeer AI — Text-to-Image](https://apis.io/schemas/livepeer/livepeer-ai-text-to-image/)
- [Livepeer Asset](https://apis.io/schemas/livepeer/livepeer-asset/)
- [Livepeer Stream](https://apis.io/schemas/livepeer/livepeer-stream/)
- [Livepeer Task](https://apis.io/schemas/livepeer/livepeer-task/)
- [Livepeer Webhook](https://apis.io/schemas/livepeer/livepeer-webhook/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Livepeer Platform Structure](https://apis.io/json-structure/livepeer/livepeer-platform-structure/)
- [Livepeer Stream Structure](https://apis.io/json-structure/livepeer/livepeer-stream-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Livepeer Context](https://apis.io/jsonld/livepeer/livepeer-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Livepeer Vocabulary](https://apis.io/vocabularies/livepeer/livepeer-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Livepeer Ai Text To Image Example](https://apis.io/examples/livepeer/livepeer-ai-text-to-image-example/)
- [Livepeer Create Stream Example](https://apis.io/examples/livepeer/livepeer-create-stream-example/)
- [Livepeer Create Webhook Example](https://apis.io/examples/livepeer/livepeer-create-webhook-example/)
- [Livepeer Image To Video Example](https://apis.io/examples/livepeer/livepeer-image-to-video-example/)

#### Collections (28)

Postman and Open Collection request collections.

- [Livepeer API Reference](https://apis.io/collections/livepeer/open-livepeer/)
- [Livepeer API Reference accessControl API](https://apis.io/collections/livepeer/open-livepeer-accesscontrol-api/)
- [Livepeer AI Runner](https://apis.io/collections/livepeer/open-livepeer-ai-worker/)
- [Livepeer API Reference accessControl asset API](https://apis.io/collections/livepeer/open-livepeer-asset-api/)
- [Livepeer CLI Local HTTP API](https://apis.io/collections/livepeer/open-livepeer-cli-http/)
- [Livepeer AI Runner accessControl Ethereum API](https://apis.io/collections/livepeer/open-livepeer-ethereum-api/)
- [Livepeer AI Runner](https://apis.io/collections/livepeer/open-livepeer-gateway/)
- [Livepeer AI Runner accessControl Gateway API](https://apis.io/collections/livepeer/open-livepeer-gateway-api/)
- [Livepeer API Reference accessControl generate API](https://apis.io/collections/livepeer/open-livepeer-generate-api/)
- [Livepeer AI Runner accessControl Hardware API](https://apis.io/collections/livepeer/open-livepeer-hardware-api/)
- [Livepeer AI Runner accessControl Health API](https://apis.io/collections/livepeer/open-livepeer-health-api/)
- [Livepeer API Reference accessControl metrics API](https://apis.io/collections/livepeer/open-livepeer-metrics-api/)
- [Livepeer API Reference accessControl multistream API](https://apis.io/collections/livepeer/open-livepeer-multistream-api/)
- [Livepeer AI Runner accessControl Orchestrator API](https://apis.io/collections/livepeer/open-livepeer-orchestrator-api/)
- [Livepeer API Reference accessControl playback API](https://apis.io/collections/livepeer/open-livepeer-playback-api/)
- [Livepeer API Reference accessControl room API](https://apis.io/collections/livepeer/open-livepeer-room-api/)
- [Livepeer API Reference accessControl session API](https://apis.io/collections/livepeer/open-livepeer-session-api/)
- [Livepeer AI Runner accessControl Staking API](https://apis.io/collections/livepeer/open-livepeer-staking-api/)
- [Livepeer AI Runner accessControl Status API](https://apis.io/collections/livepeer/open-livepeer-status-api/)
- [Livepeer API Reference accessControl stream API](https://apis.io/collections/livepeer/open-livepeer-stream-api/)
- [Livepeer API Reference](https://apis.io/collections/livepeer/open-livepeer-studio/)
- [Livepeer API Reference accessControl task API](https://apis.io/collections/livepeer/open-livepeer-task-api/)
- [Livepeer API Reference accessControl transcode API](https://apis.io/collections/livepeer/open-livepeer-transcode-api/)
- [Livepeer API Reference accessControl webhook API](https://apis.io/collections/livepeer/open-livepeer-webhook-api/)
- [Livepeer AI Runner](https://apis.io/collections/livepeer/postman-livepeer-ai-worker/)
- …and 3 more published on APIs.io

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Livepeer — ai rules](https://apis.io/rules/livepeer/livepeer-ai-rules/)
- [Livepeer — jsonschema rules](https://apis.io/rules/livepeer/livepeer-jsonschema-spectral-rules/)
- [Livepeer — studio rules](https://apis.io/rules/livepeer/livepeer-studio-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Livepeer Authentication](https://apis.io/security/livepeer/livepeer-authentication/)
- [Livepeer Domain Security](https://apis.io/security/livepeer/livepeer-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Livepeer Plans Pricing](https://apis.io/plans/livepeer/livepeer-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Livepeer Rate Limits](https://apis.io/rate-limits/livepeer/livepeer-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Livepeer Finops](https://apis.io/finops/livepeer/livepeer-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://livepeer.org/)
- [Documentation](https://docs.livepeer.org/)
- [API reference](https://docs.livepeer.org/api-reference)
- [Pricing](https://livepeer.studio/pricing)
- [Changelog](https://docs.livepeer.org/changelog)
- [Blog](https://livepeer.org/blog)
- [Terms of service](https://www.livepeer.org/legal/terms-of-service)
- [Privacy policy](https://www.livepeer.org/legal/privacy-policy)
- [GitHub](https://github.com/livepeer)
- [Status](https://status.livepeer.studio)

## API Evangelist rating

**Kin Score 39.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 53.2 |
| Contract governance | 27.3 |
| Operational transparency | 28.9 |
| Developer ergonomics | 36.9 |
| Access clarity | 22.4 |

**Agent readiness 26.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/livepeer/](https://apis.io/providers/livepeer/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Livepeer: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/livepeer/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
