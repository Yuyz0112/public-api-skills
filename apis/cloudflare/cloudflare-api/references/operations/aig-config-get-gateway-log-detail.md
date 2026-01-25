# GET /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/logs/{id}

**Resource:** [AI Gateway Logs](../resources/AI-Gateway-Logs.md)
**Get Gateway Log Detail**
**Operation ID:** `aig-config-get-gateway-log-detail`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the log details |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
