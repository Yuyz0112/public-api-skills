# GET /accounts/{account_id}/stream/{identifier}

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**Retrieve video details**
**Operation ID:** `stream-videos-retrieve-video-details`

Fetches details for a single video.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve video details response. |
| 4XX | Retrieve video details response failure. |

**Success Response Schema:**

[stream_video_response_single](../schemas/stream/stream-video-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
