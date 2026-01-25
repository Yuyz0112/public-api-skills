# POST /accounts/{account_id}/stream/watermarks

**Resource:** [Stream Watermark Profile](../resources/Stream-Watermark-Profile.md)
**Create watermark profiles via basic upload**
**Operation ID:** `stream-watermark-profile-create-watermark-profiles-via-basic-upload`

Creates watermark profiles using a single `HTTP POST multipart/form-data` request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema:** [stream_watermark_basic_upload](../schemas/stream/stream-watermark-basic-upload.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create watermark profiles via basic upload response. |
| 4XX | Create watermark profiles via basic upload response failure. |

**Success Response Schema:**

[stream_watermark_response_single](../schemas/stream/stream-watermark-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
