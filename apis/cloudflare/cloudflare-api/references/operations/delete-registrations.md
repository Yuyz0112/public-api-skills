# DELETE /accounts/{account_id}/devices/registrations

**Resource:** [Physical Devices](../resources/Physical-Devices.md)
**Delete registrations**
**Operation ID:** `delete-registrations`

Deletes a list of WARP registrations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `id` | query | string[] | Yes | A list of registration IDs to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a list of registrations response. |

## Security

- **api_token**
