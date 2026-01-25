# DELETE /accounts/{account_id}/cni/interconnects/{icon}

**Resource:** [Interconnects](../resources/Interconnects.md)
**Delete an interconnect object**
**Operation ID:** `delete_interconnect`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `icon` | path | string | Yes | Interconnect name to retrieve information about |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted interconnect |
| 400 | Bad request |
| 404 | Interconnect not found |
| 500 | Internal server error |

## Security

- **api_email**
- **api_key**
- **api_token**
