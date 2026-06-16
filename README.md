# Last.fm (last-fm)

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
