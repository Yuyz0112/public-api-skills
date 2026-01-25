# POST /accounts/{account_id}/devices/revoke

**Resource:** [Devices](../resources/Devices.md)
**Revoke devices (deprecated)**
**Operation ID:** `devices-revoke-devices`
⚠️ **Deprecated**

Revokes a list of devices. Not supported when [multi-user mode](https://developers.cloudflare.com/cloudflare-one/connections/connect-devices/warp/deployment/mdm-deployment/windows-multiuser/) is enabled.

**Deprecated**: please use POST /accounts/{account_id}/devices/registrations/revoke instead.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [teams-devices_revoke_devices_request](../schemas/teams-devices/teams-devices-revoke-devices-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Revoke devices response. |
| 4XX | Revoke devices response failure. |

**Success Response Schema:**

[teams-devices_api-response-single](../schemas/teams-devices/teams-devices-api-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
