# GET /accounts/{account_id}/devices/physical-devices/{device_id}

**Resource:** [Physical Devices](../resources/Physical-Devices.md)
**Get device**
**Operation ID:** `get-device`

Fetches a single WARP device.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `device_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a Device. |

## Security

- **api_token**
