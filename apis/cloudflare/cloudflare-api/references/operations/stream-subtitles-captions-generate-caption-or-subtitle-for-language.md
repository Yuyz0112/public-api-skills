# POST /accounts/{account_id}/stream/{identifier}/captions/{language}/generate

**Resource:** [Stream Subtitles/Captions](../resources/Stream-Subtitles-Captions.md)
**Generate captions or subtitles for a provided language via AI**
**Operation ID:** `stream-subtitles/-captions-generate-caption-or-subtitle-for-language`

Generate captions or subtitles for provided language via AI.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `language` | path | stream_language | Yes |  |
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Generate captions or subtitles response for a provided language. |
| 4XX | Generate captions or subtitles response for a provided language. |

**Success Response Schema:**

[stream_language_response_single](../schemas/stream/stream-language-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
