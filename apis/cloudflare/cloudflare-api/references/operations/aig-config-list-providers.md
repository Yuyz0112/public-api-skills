# GET /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/provider_configs

**Resource:** [AI Gateway Provider Configs](../resources/AI-Gateway-Provider-Configs.md)
**List Provider Configs**
**Operation ID:** `aig-config-list-providers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List objects |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
