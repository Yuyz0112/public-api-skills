# GET /accounts/{account_id}/cni/slots/{slot}

**Resource:** [Slots](../resources/Slots.md)
**Get information about the specified slot**
**Operation ID:** `get_slot`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slot` | path | string (uuid) | Yes |  |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Information about the specified slot |
| 400 | Bad request |
| 404 | Slot not found |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_SlotInfo](../schemas/nsc/nsc-SlotInfo.md)

## Security

- **api_email**
- **api_key**
- **api_token**
