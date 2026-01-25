# POST /accounts/{account_id}/devices/unrevoke

**Resource:** [Devices](../resources/Devices.md)
**Unrevoke devices (deprecated)**
**Operation ID:** `devices-unrevoke-devices`
⚠️ **Deprecated**

Unrevokes a list of devices. Not supported when [multi-user mode](https://developers.cloudflare.com/cloudflare-one/connections/connect-devices/warp/deployment/mdm-deployment/windows-multiuser/) is enabled.

**Deprecated**: please use POST /accounts/{account_id}/devices/registrations/unrevoke instead.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [teams-devices_unrevoke_devices_request](../schemas/teams-devices/teams-devices-unrevoke-devices-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Unrevoke devices response. |
| 4XX | Unrevoke devices response failure. |

**Success Response Schema:**

[teams-devices_api-response-single](../schemas/teams-devices/teams-devices-api-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
