# POST /accounts/{account_id}/devices/physical-devices/{device_id}/revoke

**Resource:** [Physical Devices](../resources/Physical-Devices.md)
**Revoke device registrations**
**Operation ID:** `revoke-device`

Revokes all WARP registrations associated with the specified device.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `device_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Revoke device registrations response. |

## Security

- **api_token**
