# GET /accounts/{account_id}/stream/{identifier}/downloads

**Resource:** [Stream MP4 Downloads](../resources/Stream-MP4-Downloads.md)
**List downloads**
**Operation ID:** `stream-m-p-4-downloads-list-downloads`

Lists the downloads created for a video.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List downloads response. |
| 4XX | List downloads response failure. |

**Success Response Schema:**

[stream_downloads_response](../schemas/stream/stream-downloads-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
