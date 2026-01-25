# POST /accounts/{account_id}/ai-gateway/gateways

**Resource:** [AI Gateway Gateways](../resources/AI-Gateway-Gateways.md)
**Create a new Gateway**
**Operation ID:** `aig-config-create-gateway`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the created Object |
| 400 | Input Validation Error |

## Security

- **api_token**
- **api_email**
- **api_key**
