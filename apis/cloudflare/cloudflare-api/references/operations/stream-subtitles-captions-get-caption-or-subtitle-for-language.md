# GET /accounts/{account_id}/stream/{identifier}/captions/{language}

**Resource:** [Stream Subtitles/Captions](../resources/Stream-Subtitles-Captions.md)
**List captions or subtitles for a provided language**
**Operation ID:** `stream-subtitles/-captions-get-caption-or-subtitle-for-language`

Lists the captions or subtitles for provided language.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `language` | path | stream_language | Yes |  |
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List captions or subtitles response for a provided language. |
| 4XX | List captions or subtitles response for a provided language. |

**Success Response Schema:**

[stream_language_response_single](../schemas/stream/stream-language-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
