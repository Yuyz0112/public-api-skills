# POST /accounts/{account_id}/stream/{identifier}

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**Edit video details**
**Operation ID:** `stream-videos-update-video-details`

Edit details for a single video.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_video_update](../schemas/stream/stream-video-update.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit video details response. |
| 4XX | Edit video details response failure. |

**Success Response Schema:**

[stream_video_response_single](../schemas/stream/stream-video-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
