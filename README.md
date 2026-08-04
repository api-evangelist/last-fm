# Last.fm (last-fm)

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

Last.fm is a music discovery and social listening platform that tracks users' listening habits across devices and services via scrobbling. The Last.fm API provides access to a rich music metadata database covering artist information, album data, track details, user listening history, personalized charts, and music recommendations. Developers can integrate scrobbling, retrieve top charts by geography or tag, explore similar artists and tracks, and access user profile data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/last-fm/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/last-fm/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Music
- Music Metadata
- Scrobbling
- Music Discovery
- Streaming

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Last.fm API

The Last.fm API provides access to the Last.fm music platform, enabling developers to retrieve music metadata for artists, albums, and tracks; read and write user scrobble data; explore personalized recommendations; access global and geographic music charts; search the music catalog; and retrieve user listening histories and social data such as friends and loved tracks. Authentication is required for write operations including scrobbling. The API uses REST over HTTP with responses available in JSON or XML format.

- **Human URL:** [https://www.last.fm/api](https://www.last.fm/api)
- **Base URL:** `https://ws.audioscrobbler.com/2.0/`

#### Tags

- Music
- Artists
- Albums
- Tracks
- Scrobbling
- Charts
- Users

#### Properties

- [Documentation](https://www.last.fm/api)
- [Getting Started](https://www.last.fm/api/intro)
- [Authentication](https://www.last.fm/api/authentication)
- [Terms of Service](https://www.last.fm/api/tos)
- [OpenAPI](openapi/last-fm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [J S O N L D Context](json-ld/last-fm-context.jsonld)
- [JSON Schema](json-schema/artist.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/track.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/scrobble.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/last-fm-vocabulary.yml)
- [Example](examples/artist-getInfo-response.json)
- [Example](examples/track-scrobble-request.json)
- [Example](examples/user-getRecentTracks-response.json)

## Common Properties

- [Website](https://www.last.fm/)
- [Documentation](https://www.last.fm/api)
- [Getting Started](https://www.last.fm/api/intro)
- [Authentication](https://www.last.fm/api/authentication)
- [Terms of Service](https://www.last.fm/api/tos)
- [GitHub Organization](https://github.com/lastfm)
- [LinkedIn](https://www.linkedin.com/company/last-fm)
- [Blog](https://www.last.fm/blog)
- [Pricing](https://www.last.fm/pro)
- [X (Twitter)](https://x.com/lastfm)
- [Status Page](https://x.com/lastfmstatus)
- [Plans](plans/last-fm-plans-pricing.yml)
- [Rate Limits](rate-limits/last-fm-rate-limits.yml)
- [Fin Ops](finops/last-fm-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
