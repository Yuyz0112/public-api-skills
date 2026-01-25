# GET /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/evaluations/{id}

**Resource:** [AI Gateway Evaluations](../resources/AI-Gateway-Evaluations.md)
**Fetch a Evaluation**
**Operation ID:** `aig-config-fetch-evaluations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `gateway_id` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a single object if found |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
