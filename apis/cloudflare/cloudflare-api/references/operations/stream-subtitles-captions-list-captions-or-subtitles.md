# GET /accounts/{account_id}/stream/{identifier}/captions

**Resource:** [Stream Subtitles/Captions](../resources/Stream-Subtitles-Captions.md)
**List captions or subtitles**
**Operation ID:** `stream-subtitles/-captions-list-captions-or-subtitles`

Lists the available captions or subtitles for a specific video.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List captions or subtitles response. |
| 4XX | List captions or subtitles response failure. |

**Success Response Schema:**

[stream_language_response_collection](../schemas/stream/stream-language-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
