# GET /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/url/{provider}

**Resource:** [AI Gateway Gateways](../resources/AI-Gateway-Gateways.md)
**Get Gateway URL**
**Operation ID:** `aig-config-get-gateway-url`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `gateway_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |
| `provider` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the log details |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
