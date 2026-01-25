# GET /accounts/{account_id}/stream/watermarks

**Resource:** [Stream Watermark Profile](../resources/Stream-Watermark-Profile.md)
**List watermark profiles**
**Operation ID:** `stream-watermark-profile-list-watermark-profiles`

Lists all watermark profiles for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List watermark profiles response. |
| 4XX | List watermark profiles response failure. |

**Success Response Schema:**

[stream_watermark_response_collection](../schemas/stream/stream-watermark-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
