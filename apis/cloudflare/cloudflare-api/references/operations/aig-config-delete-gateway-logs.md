# DELETE /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/logs

**Resource:** [AI Gateway Logs](../resources/AI-Gateway-Logs.md)
**Delete Gateway Logs**
**Operation ID:** `aig-config-delete-gateway-logs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `order_by` | query | enum: created_at, provider, model... | No |  |
| `order_by_direction` | query | enum: asc, desc | No |  |
| `filters` | query | object[] | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns if the delete was successful |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
