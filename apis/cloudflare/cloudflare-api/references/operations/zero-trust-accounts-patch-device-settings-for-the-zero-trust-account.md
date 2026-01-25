# PATCH /accounts/{account_id}/devices/settings

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Patch device settings for a Zero Trust account**
**Operation ID:** `zero-trust-accounts-patch-device-settings-for-the-zero-trust-account`

Patches the current device settings for a Zero Trust account.

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
| 200 | Patch device settings for a Zero Trust account response. |
| 4XX | Patch device settings for a Zero Trust account response failure. |

**Success Response Schema:**

[teams-devices_zero-trust-account-device-settings-response](../schemas/teams-devices/teams-devices-zero-trust-account-device-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
