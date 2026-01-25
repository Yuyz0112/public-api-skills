# GET /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/routes/{id}

**Resource:** [AI Gateway Dynamic Routes](../resources/AI-Gateway-Dynamic-Routes.md)
**Get an AI Gateway Dynamic Route.**
**Operation ID:** `aig-config-get-gateway-dynamic-route`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
