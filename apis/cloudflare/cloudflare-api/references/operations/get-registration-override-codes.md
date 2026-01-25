# GET /accounts/{account_id}/devices/registrations/{registration_id}/override_codes

**Resource:** [warp-teams-device-api_other](../resources/warp-teams-device-api-other.md)
**Get override codes**
**Operation ID:** `get-registration-override-codes`

Fetches one-time use admin override codes for a registration. This relies on the **Admin Override** setting being enabled in your device configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `registration_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get admin override codes for a registration response. |

## Security

- **api_token**
