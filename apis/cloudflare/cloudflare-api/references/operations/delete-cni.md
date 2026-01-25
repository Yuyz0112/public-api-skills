# DELETE /accounts/{account_id}/cni/cnis/{cni}

**Resource:** [CNIs](../resources/CNIs.md)
**Delete a specified CNI object**
**Operation ID:** `delete_cni`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cni` | path | string (uuid) | Yes | CNI ID to retrieve information about |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | CNI has been successfully deleted |
| 400 | Bad request |
| 404 | CNI not found |
| 500 | Internal server error |

## Security

- **api_email**
- **api_key**
- **api_token**
