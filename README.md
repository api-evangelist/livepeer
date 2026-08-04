# Livepeer (livepeer)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Livepeer is a decentralized video infrastructure network. Independent orchestrators run GPU hardware to provide live and on-demand video transcoding services, paid for in ETH/LPT on the Livepeer protocol. Livepeer Studio is the managed gateway and developer platform sitting on top of the network, exposing a REST API at livepeer.studio/api for live streams, on- demand assets, multistream targets, transcoding jobs, sessions, playback, signing keys, AI generation (text-to-image, image-to-image, image-to-video, upscale, audio-to-text), and webhooks. Official SDKs are published for JavaScript/TypeScript, Python, Go, and Ruby, with React Player and React Broadcast components for client-side playback and ingest.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/livepeer/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/livepeer/refs/heads/main/apis.yml)

## Tags

- Video
- Streaming
- Transcoding
- Decentralized
- Web3
- Live Video
- AI Video

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Livepeer Studio REST API

Primary REST API for the Livepeer Studio gateway. Resource-oriented JSON endpoints for live streams, on-demand assets, multistream targets, transcoding jobs, sessions, playback, signing keys, webhooks, and access controls. Authenticated via API keys issued from the Livepeer Studio dashboard.

- **Human URL:** [https://docs.livepeer.org/api-reference/overview](https://docs.livepeer.org/api-reference/overview)
- **Base URL:** `https://livepeer.studio/api`

#### Tags

- REST
- Streams
- Assets
- Transcoding

#### Properties

- [Documentation](https://docs.livepeer.org/api-reference/overview)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Streams API

Endpoints for creating and managing live streams, ingest RTMP/WHIP URLs, profiles for adaptive bitrate transcoding, recording, and stream keys.

- **Human URL:** [https://docs.livepeer.org/api-reference/stream/overview](https://docs.livepeer.org/api-reference/stream/overview)
- **Base URL:** `https://livepeer.studio/api/stream`

#### Tags

- Live Streams
- RTMP
- WHIP

#### Properties

- [Documentation](https://docs.livepeer.org/api-reference/stream/overview)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Assets API

Endpoints for uploading, importing, transcoding, and serving on-demand video assets, including direct upload, URL import, and IPFS storage.

- **Human URL:** [https://docs.livepeer.org/api-reference/asset/overview](https://docs.livepeer.org/api-reference/asset/overview)
- **Base URL:** `https://livepeer.studio/api/asset`

#### Tags

- VOD
- Assets
- IPFS

#### Properties

- [Documentation](https://docs.livepeer.org/api-reference/asset/overview)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Multistream Targets API

Endpoints for registering and managing multistream destinations that forward an active live stream to additional RTMP/RTMPS endpoints such as YouTube, Twitch, or X.

- **Human URL:** [https://docs.livepeer.org/api-reference/multistream-target/overview](https://docs.livepeer.org/api-reference/multistream-target/overview)
- **Base URL:** `https://livepeer.studio/api/multistream/target`

#### Tags

- Multistream
- Restream

#### Properties

- [Documentation](https://docs.livepeer.org/api-reference/multistream-target/overview)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Webhooks API

Webhook management endpoints plus outbound event notifications for stream lifecycle events (stream.started, stream.idle, recording.ready, asset.ready, playback.access_control). Signed payloads delivered to customer-configured URLs.

- **Human URL:** [https://docs.livepeer.org/api-reference/webhook/overview](https://docs.livepeer.org/api-reference/webhook/overview)
- **Base URL:** `https://livepeer.studio/api/webhook`

#### Tags

- Webhooks
- Events
- Callbacks

#### Properties

- [Documentation](https://docs.livepeer.org/api-reference/webhook/overview)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Transcode API

Endpoints for one-off transcoding jobs against source files in object storage, returning a job handle and transcoded renditions.

- **Human URL:** [https://docs.livepeer.org/api-reference/transcode/overview](https://docs.livepeer.org/api-reference/transcode/overview)
- **Base URL:** `https://livepeer.studio/api/transcode`

#### Tags

- Transcoding
- Jobs

#### Properties

- [Documentation](https://docs.livepeer.org/api-reference/transcode/overview)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Sessions API

Endpoints for retrieving completed live session recordings and metadata for past live streams.

- **Human URL:** [https://docs.livepeer.org/api-reference/session/overview](https://docs.livepeer.org/api-reference/session/overview)
- **Base URL:** `https://livepeer.studio/api/session`

#### Tags

- Sessions
- Recordings

#### Properties

- [Documentation](https://docs.livepeer.org/api-reference/session/overview)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Playback API

Playback info endpoint returning HLS/WebRTC playback URLs and metadata for a stream or asset, plus access-control gating.

- **Human URL:** [https://docs.livepeer.org/api-reference/playback/overview](https://docs.livepeer.org/api-reference/playback/overview)
- **Base URL:** `https://livepeer.studio/api/playback`

#### Tags

- Playback
- HLS
- WebRTC

#### Properties

- [Documentation](https://docs.livepeer.org/api-reference/playback/overview)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Signing Keys API

Endpoints for managing JWT signing keys used for playback access control and webhook signature verification.

- **Human URL:** [https://docs.livepeer.org/api-reference/access-control/overview](https://docs.livepeer.org/api-reference/access-control/overview)
- **Base URL:** `https://livepeer.studio/api/access-control/signing-key`

#### Tags

- Access Control
- JWT
- Signing Keys

#### Properties

- [Documentation](https://docs.livepeer.org/api-reference/access-control/overview)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer AI Generate API

AI video and image generation endpoints (text-to-image, image-to-image, image-to-video, upscale, audio-to-text) routed through the Livepeer AI subnet of GPU orchestrators.

- **Human URL:** [https://docs.livepeer.org/ai/api-reference/text-to-image](https://docs.livepeer.org/ai/api-reference/text-to-image)
- **Base URL:** `https://livepeer.studio/api/generate`

#### Tags

- AI
- Generation
- Text-to-Image
- Image-to-Video

#### Properties

- [Documentation](https://docs.livepeer.org/ai/api-reference/text-to-image)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer JavaScript/TypeScript SDK

Official TypeScript/JavaScript SDK (@livepeer/ai or livepeer) for the Livepeer Studio REST API and AI endpoints.

- **Human URL:** [https://github.com/livepeer/livepeer-js](https://github.com/livepeer/livepeer-js)
- **Base URL:** `https://github.com/livepeer/livepeer-js`

#### Tags

- SDK
- TypeScript
- JavaScript

#### Properties

- [Repository](https://github.com/livepeer/livepeer-js)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Python SDK

Official Python SDK for the Livepeer Studio REST API.

- **Human URL:** [https://github.com/livepeer/livepeer-python](https://github.com/livepeer/livepeer-python)
- **Base URL:** `https://github.com/livepeer/livepeer-python`

#### Tags

- SDK
- Python

#### Properties

- [Repository](https://github.com/livepeer/livepeer-python)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Go SDK

Official Go SDK for the Livepeer Studio REST API.

- **Human URL:** [https://github.com/livepeer/livepeer-go](https://github.com/livepeer/livepeer-go)
- **Base URL:** `https://github.com/livepeer/livepeer-go`

#### Tags

- SDK
- Go

#### Properties

- [Repository](https://github.com/livepeer/livepeer-go)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer Ruby SDK

Official Ruby SDK for the Livepeer Studio REST API.

- **Human URL:** [https://github.com/livepeer/livepeer-ruby](https://github.com/livepeer/livepeer-ruby)
- **Base URL:** `https://github.com/livepeer/livepeer-ruby`

#### Tags

- SDK
- Ruby

#### Properties

- [Repository](https://github.com/livepeer/livepeer-ruby)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer React Player Component

React video player component for HLS/WebRTC playback of Livepeer streams and assets, with customisable controls and access-control integration.

- **Human URL:** [https://docs.livepeer.org/developers/react/player](https://docs.livepeer.org/developers/react/player)
- **Base URL:** `https://github.com/livepeer/react`

#### Tags

- SDK
- React
- Player

#### Properties

- [Documentation](https://docs.livepeer.org/developers/react/player)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Livepeer React Broadcast Component

React component for in-browser WebRTC broadcasting to a Livepeer live stream, with device selection and settings controls.

- **Human URL:** [https://docs.livepeer.org/developers/react/broadcast](https://docs.livepeer.org/developers/react/broadcast)
- **Base URL:** `https://github.com/livepeer/react`

#### Tags

- SDK
- React
- Broadcast
- WebRTC

#### Properties

- [Documentation](https://docs.livepeer.org/developers/react/broadcast)
- [Postman Collection](collections/livepeer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livepeer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/livepeer)
- [Website](https://livepeer.org/)
- [Studio](https://livepeer.studio/)
- [Documentation](https://docs.livepeer.org/)
- [Git Hub](https://github.com/livepeer)
- [Status](https://status.livepeer.studio/)
- [Plans](plans/livepeer-plans-pricing.yml)
- [Rate Limits](rate-limits/livepeer-rate-limits.yml)
- [Fin Ops](finops/livepeer-finops.yml)
- [L L Ms Txt](https://docs.livepeer.org/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
