# GET /accounts/{account_id}/devices

**Resource:** [Devices](../resources/Devices.md)
**List devices (deprecated)**
**Operation ID:** `devices-list-devices`
⚠️ **Deprecated**

List WARP devices. Not supported when [multi-user mode](https://developers.cloudflare.com/cloudflare-one/connections/connect-devices/warp/deployment/mdm-deployment/windows-multiuser/) is enabled for the account.

**Deprecated**: please use one of the following endpoints instead:
- GET /accounts/{account_id}/devices/physical-devices
- GET /accounts/{account_id}/devices/registrations


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List devices response. |
| 4XX | List devices response failure. |

**Success Response Schema:**

[teams-devices_devices_response](../schemas/teams-devices/teams-devices-devices-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
