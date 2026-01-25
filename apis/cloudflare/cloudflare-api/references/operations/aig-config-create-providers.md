# POST /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/provider_configs

**Resource:** [AI Gateway Provider Configs](../resources/AI-Gateway-Provider-Configs.md)
**Create a new Provider Configs**
**Operation ID:** `aig-config-create-providers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the created Object |
| 400 | Input Validation Error |

## Security

- **api_token**
- **api_email**
- **api_key**
