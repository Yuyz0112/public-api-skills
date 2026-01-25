# GET /accounts/{account_id}/stream/watermarks/{identifier}

**Resource:** [Stream Watermark Profile](../resources/Stream-Watermark-Profile.md)
**Watermark profile details**
**Operation ID:** `stream-watermark-profile-watermark-profile-details`

Retrieves details for a single watermark profile.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_watermark_identifier | Yes |  |
| `account_id` | path | stream_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Watermark profile details response. |
| 4XX | Watermark profile details response failure. |

**Success Response Schema:**

[stream_watermark_response_single](../schemas/stream/stream-watermark-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
