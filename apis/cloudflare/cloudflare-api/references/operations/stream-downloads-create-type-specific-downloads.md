# POST /accounts/{account_id}/stream/{identifier}/downloads/{download_type}

**Resource:** [Stream MP4 Downloads](../resources/Stream-MP4-Downloads.md)
**Create download**
**Operation ID:** `stream-downloads-create-type-specific-downloads`

Creates a download for a video of specified type. For backwards-compatibility, POST requests to /downloads will enable the default download.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |
| `download_type` | path | stream_download_type | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create download of specified type response. |
| 4XX | Create downloads of specified type response failure. |

**Success Response Schema:**

[stream_downloads_response](../schemas/stream/stream-downloads-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
