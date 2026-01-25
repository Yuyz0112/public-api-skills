# GET /accounts/{account_id}/stream/{identifier}/captions/{language}/vtt

**Resource:** [Stream Subtitles/Captions](../resources/Stream-Subtitles-Captions.md)
**Return WebVTT captions for a provided language**
**Operation ID:** `stream-subtitles/-captions-get-vtt-caption-or-subtitle`

Return WebVTT captions for a provided language.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `language` | path | stream_language | Yes |  |
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Return WebVTT caption or subtitle response. |
| 4XX | Return WebVTT caption or subtitle response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
