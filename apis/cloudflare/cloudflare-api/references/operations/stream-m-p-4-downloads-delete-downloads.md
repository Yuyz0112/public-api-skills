# DELETE /accounts/{account_id}/stream/{identifier}/downloads

**Resource:** [Stream MP4 Downloads](../resources/Stream-MP4-Downloads.md)
**Delete downloads**
**Operation ID:** `stream-m-p-4-downloads-delete-downloads`

Delete the downloads for a video. Use `/downloads/{download_type}` instead for type-specific downloads. Available types are `default` and `audio`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete downloads response. |
| 4XX | Delete downloads response failure. |

**Success Response Schema:**

[stream_deleted_response](../schemas/stream/stream-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
