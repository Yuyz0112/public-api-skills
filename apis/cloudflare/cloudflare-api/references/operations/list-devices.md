# GET /accounts/{account_id}/devices/physical-devices

**Resource:** [Physical Devices](../resources/Physical-Devices.md)
**List devices**
**Operation ID:** `list-devices`

Lists WARP devices.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of Devices. |

## Security

- **api_token**
