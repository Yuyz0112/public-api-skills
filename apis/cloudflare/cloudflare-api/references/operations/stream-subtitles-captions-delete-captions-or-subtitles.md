# DELETE /accounts/{account_id}/stream/{identifier}/captions/{language}

**Resource:** [Stream Subtitles/Captions](../resources/Stream-Subtitles-Captions.md)
**Delete captions or subtitles**
**Operation ID:** `stream-subtitles/-captions-delete-captions-or-subtitles`

Removes the captions or subtitles from a video.

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
| 200 | Delete captions or subtitles response. |
| 4XX | Delete captions or subtitles response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
