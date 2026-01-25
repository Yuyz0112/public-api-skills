# DELETE /accounts/{account_id}/devices/physical-devices/{device_id}

**Resource:** [Physical Devices](../resources/Physical-Devices.md)
**Delete device**
**Operation ID:** `delete-device`

Deletes a WARP device.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `device_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Device was successfully deleted. |

## Security

- **api_token**
