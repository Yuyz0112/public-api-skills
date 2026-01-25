# GET /accounts/{account_id}/ai-gateway/gateways/{id}

**Resource:** [AI Gateway Gateways](../resources/AI-Gateway-Gateways.md)
**Fetch a Gateway**
**Operation ID:** `aig-config-fetch-gateway`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
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
