# POST /accounts/{account_id}/stream/clip

**Resource:** [Stream Video Clipping](../resources/Stream-Video-Clipping.md)
**Clip videos given a start and end time**
**Operation ID:** `stream-video-clipping-clip-videos-given-a-start-and-end-time`

Clips a video based on the specified start and end times provided in seconds.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_videoClipStandard](../schemas/stream/stream-videoClipStandard.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Clip videos given a start and end time response. |
| 4XX | Clip videos given a start and end time response failure. |

**Success Response Schema:**

[stream_clipResponseSingle](../schemas/stream/stream-clipResponseSingle.md)

## Security

- **api_email**
- **api_key**
- **api_token**
