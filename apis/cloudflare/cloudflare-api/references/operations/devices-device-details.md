# GET /accounts/{account_id}/devices/{device_id}

**Resource:** [Devices](../resources/Devices.md)
**Get device (deprecated)**
**Operation ID:** `devices-device-details`
⚠️ **Deprecated**

Fetches a single WARP device. Not supported when [multi-user mode](https://developers.cloudflare.com/cloudflare-one/connections/connect-devices/warp/deployment/mdm-deployment/windows-multiuser/) is enabled for the account.

**Deprecated**: please use one of the following endpoints instead:
- GET /accounts/{account_id}/devices/physical-devices/{device_id}
- GET /accounts/{account_id}/devices/registrations/{registration_id}


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `device_id` | path | teams-devices_registration_id | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get device details response. |
| 4XX | Get device details response failure. |

**Success Response Schema:**

[teams-devices_device_response](../schemas/teams-devices/teams-devices-device-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
