# POST /accounts/{account_id}/stream/{identifier}/downloads

**Resource:** [Stream MP4 Downloads](../resources/Stream-MP4-Downloads.md)
**Create downloads**
**Operation ID:** `stream-m-p-4-downloads-create-downloads`

Creates a download for a video when a video is ready to view. Use `/downloads/{download_type}` instead for type-specific downloads. Available types are `default` and `audio`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create downloads response. |
| 4XX | Create downloads response failure. |

**Success Response Schema:**

[stream_downloads_response_single](../schemas/stream/stream-downloads-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
