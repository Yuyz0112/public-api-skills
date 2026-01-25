# GET /accounts/{account_id}/ai-gateway/gateways

**Resource:** [AI Gateway Gateways](../resources/AI-Gateway-Gateways.md)
**List Gateways**
**Operation ID:** `aig-config-list-gateway`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List objects |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
