# DELETE /accounts/{account_id}/ai-gateway/gateways/{id}

**Resource:** [AI Gateway Gateways](../resources/AI-Gateway-Gateways.md)
**Delete a Gateway**
**Operation ID:** `aig-config-delete-gateway`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the Object if it was successfully deleted |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
