# PATCH /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/routes/{id}

**Resource:** [AI Gateway Dynamic Routes](../resources/AI-Gateway-Dynamic-Routes.md)
**Update an AI Gateway Dynamic Route.**
**Operation ID:** `aig-config-update-gateway-dynamic-route`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | Input Error |

## Security

- **api_token**
- **api_email**
- **api_key**
