# DELETE /accounts/{account_id}/stream/watermarks/{identifier}

**Resource:** [Stream Watermark Profile](../resources/Stream-Watermark-Profile.md)
**Delete watermark profiles**
**Operation ID:** `stream-watermark-profile-delete-watermark-profiles`

Deletes a watermark profile.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_watermark_identifier | Yes |  |
| `account_id` | path | stream_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete watermark profiles response. |
| 4XX | Delete watermark profiles response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
