# PATCH /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/logs/{id}

**Resource:** [AI Gateway Logs](../resources/AI-Gateway-Logs.md)
**Patch Gateway Log**
**Operation ID:** `aig-config-patch-gateway-log`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the log details |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
