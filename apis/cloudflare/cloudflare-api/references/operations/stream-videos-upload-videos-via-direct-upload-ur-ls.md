# POST /accounts/{account_id}/stream/direct_upload

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**Upload videos via direct upload URLs**
**Operation ID:** `stream-videos-upload-videos-via-direct-upload-ur-ls`

Creates a direct upload that allows video uploads without an API key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |
| `Upload-Creator` | header | stream_creator | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_direct_upload_request](../schemas/stream/stream-direct-upload-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upload videos via direct upload URLs response. |
| 4XX | Upload videos via direct upload URLs response failure. |

**Success Response Schema:**

[stream_direct_upload_response](../schemas/stream/stream-direct-upload-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
