# GET /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/logs

**Resource:** [AI Gateway Logs](../resources/AI-Gateway-Logs.md)
**List Gateway Logs**
**Operation ID:** `aig-config-list-gateway-logs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `search` | query | string | No |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `order_by` | query | enum: created_at, provider, model... | No |  |
| `order_by_direction` | query | enum: asc, desc | No |  |
| `filters` | query | object[] | No |  |
| `meta_info` | query | boolean | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `start_date` | query | string (date-time) | No |  |
| `end_date` | query | string (date-time) | No |  |
| `min_cost` | query | number | No |  |
| `max_cost` | query | number | No |  |
| `min_tokens_in` | query | number | No |  |
| `max_tokens_in` | query | number | No |  |
| `min_tokens_out` | query | number | No |  |
| `max_tokens_out` | query | number | No |  |
| `min_total_tokens` | query | number | No |  |
| `max_total_tokens` | query | number | No |  |
| `min_duration` | query | number | No |  |
| `max_duration` | query | number | No |  |
| `feedback` | query | any | No |  |
| `success` | query | boolean | No |  |
| `cached` | query | boolean | No |  |
| `model` | query | string | No |  |
| `model_type` | query | string | No |  |
| `provider` | query | string | No |  |
| `request_content_type` | query | string | No |  |
| `response_content_type` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of Gateway Logs |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
