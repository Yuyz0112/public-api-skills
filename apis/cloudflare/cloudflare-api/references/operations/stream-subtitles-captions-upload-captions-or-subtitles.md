# PUT /accounts/{account_id}/stream/{identifier}/captions/{language}

**Resource:** [Stream Subtitles/Captions](../resources/Stream-Subtitles-Captions.md)
**Upload captions or subtitles**
**Operation ID:** `stream-subtitles/-captions-upload-captions-or-subtitles`

Uploads the caption or subtitle file to the endpoint for a specific BCP47 language. One caption or subtitle file per language is allowed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `language` | path | stream_language | Yes |  |
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema:** [stream_caption_basic_upload](../schemas/stream/stream-caption-basic-upload.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upload captions or subtitles response. |
| 4XX | Upload captions or subtitles response failure. |

**Success Response Schema:**

[stream_language_response_single](../schemas/stream/stream-language-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
