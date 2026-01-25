# GET /accounts/{account_id}/cni/slots

**Resource:** [Slots](../resources/Slots.md)
**Retrieve a list of all slots matching the specified parameters**
**Operation ID:** `list_slots`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `address_contains` | query | string | No | If specified, only show slots with the given text in their address field |
| `site` | query | string | No | If specified, only show slots located at the given site |
| `speed` | query | string | No | If specified, only show slots that support the given speed |
| `occupied` | query | boolean | No | If specified, only show slots with a specific occupied/unoccupied state |
| `cursor` | query | integer (int32) | No |  |
| `limit` | query | integer | No |  |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of matching slots |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_SlotList](../schemas/nsc/nsc-SlotList.md)

## Security

- **api_email**
- **api_key**
- **api_token**
