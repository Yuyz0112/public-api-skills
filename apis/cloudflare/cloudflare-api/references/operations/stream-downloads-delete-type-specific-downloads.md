# DELETE /accounts/{account_id}/stream/{identifier}/downloads/{download_type}

**Resource:** [Stream MP4 Downloads](../resources/Stream-MP4-Downloads.md)
**Delete download**
**Operation ID:** `stream-downloads-delete-type-specific-downloads`

Delete specific type of download. For backwards-compatibility, DELETE requests to /downloads will delete the default download.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |
| `download_type` | path | stream_download_type | Yes |  |

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
