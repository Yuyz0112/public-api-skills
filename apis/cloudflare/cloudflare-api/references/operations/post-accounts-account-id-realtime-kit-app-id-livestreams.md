# POST /accounts/{account_id}/realtime/kit/{app_id}/livestreams

**Resource:** [Live streams](../resources/Live-streams.md)
**Create an independent livestream**
**Operation ID:** `post--accounts-{account_id}-realtime-kit-{app_id}-livestreams`

Creates a livestream for the given App ID and returns ingest server, stream key, and playback URL. You can pass custom input to the ingest server and stream key, and freely distribute the content using the playback URL on any player that supports HLS/LHLS.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successful response |

## Security

- **api_token**
