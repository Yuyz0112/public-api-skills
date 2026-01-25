# PUT /accounts/{account_id}/devices/settings

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Update device settings for a Zero Trust account**
**Operation ID:** `zero-trust-accounts-update-device-settings-for-the-zero-trust-account`

Updates the current device settings for a Zero Trust account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [teams-devices_zero-trust-account-device-settings](../schemas/teams-devices/teams-devices-zero-trust-account-device-settings.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update device settings for a Zero Trust account response. |
| 4XX | Update device settings for a Zero Trust account response failure. |

**Success Response Schema:**

[teams-devices_zero-trust-account-device-settings-response](../schemas/teams-devices/teams-devices-zero-trust-account-device-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
