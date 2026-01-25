# GET /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/evaluations

**Resource:** [AI Gateway Evaluations](../resources/AI-Gateway-Evaluations.md)
**List Evaluations**
**Operation ID:** `aig-config-list-evaluations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `name` | query | string | No |  |
| `processed` | query | boolean | No |  |
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
