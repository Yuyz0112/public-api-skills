# DELETE /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/provider_configs/{id}

**Resource:** [AI Gateway Provider Configs](../resources/AI-Gateway-Provider-Configs.md)
**Delete a Provider Configs**
**Operation ID:** `aig-config-delete-providers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
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
