# GET /accounts/{account_id}/ai-gateway/evaluation-types

**Resource:** [AI Gateway Evaluations](../resources/AI-Gateway-Evaluations.md)
**List Evaluators**
**Operation ID:** `aig-config-list-evaluators`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `order_by` | query | string | No |  |
| `order_by_direction` | query | enum: asc, desc | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of Evaluators |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
