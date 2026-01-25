# PUT /accounts/{account_id}/ai-gateway/gateways/{id}

**Resource:** [AI Gateway Gateways](../resources/AI-Gateway-Gateways.md)
**Update a Gateway**
**Operation ID:** `aig-config-update-gateway`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated Object |
| 400 | Input Validation Error |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
