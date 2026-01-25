# GET /accounts/{account_id}/devices/{device_id}/override_codes

**Resource:** [Devices](../resources/Devices.md)
**Get override codes (deprecated)
**
**Operation ID:** `devices-list-admin-override-code-for-device`
⚠️ **Deprecated**

Fetches a one-time use admin override code for a device. This relies on the **Admin Override** setting being enabled in your device configuration. Not supported when [multi-user mode](https://developers.cloudflare.com/cloudflare-one/connections/connect-devices/warp/deployment/mdm-deployment/windows-multiuser/) is enabled for the account.
**Deprecated:** please use GET /accounts/{account_id}/devices/registrations/{registration_id}/override_codes instead.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `device_id` | path | teams-devices_registration_id | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an admin override code for a device response. |
| 4XX | Get an admin override code for a device response failure. |

**Success Response Schema:**

[teams-devices_override_codes_response](../schemas/teams-devices/teams-devices-override-codes-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
