# PUT /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/provider_configs/{id}

**Resource:** [AI Gateway Provider Configs](../resources/AI-Gateway-Provider-Configs.md)
**Update a Provider Configs**
**Operation ID:** `aig-config-update-providers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated Object |
| 400 | Input Validation Error |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
