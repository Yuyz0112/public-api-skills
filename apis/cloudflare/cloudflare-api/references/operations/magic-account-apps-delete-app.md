# DELETE /accounts/{account_id}/magic/apps/{account_app_id}

**Resource:** [Magic Account Apps](../resources/Magic-Account-Apps.md)
**Delete Account App**
**Operation ID:** `magic-account-apps-delete-app`

Deletes specific Account App.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `account_app_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete App response |
| 4XX | Delete App response failure |

**Success Response Schema:**

[magic_app_single_response](../schemas/magic/magic-app-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
