# GET /accounts/{account_id}/stream

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**List videos**
**Operation ID:** `stream-videos-list-videos`

Lists up to 1000 videos from a single request. For a specific range, refer to the optional parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |
| `status` | query | stream_media_state | No |  |
| `creator` | query | stream_creator | No |  |
| `type` | query | stream_type | No |  |
| `asc` | query | stream_asc | No |  |
| `video_name` | query | stream_video_name | No |  |
| `search` | query | stream_search | No |  |
| `start` | query | stream_start | No |  |
| `end` | query | stream_end | No |  |
| `include_counts` | query | stream_include_counts | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List videos response. |
| 4XX | List videos response failure. |

**Success Response Schema:**

[stream_video_response_collection](../schemas/stream/stream-video-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
