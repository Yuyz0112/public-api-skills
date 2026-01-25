# PUT /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/datasets/{id}

**Resource:** [AI Gateway Datasets](../resources/AI-Gateway-Datasets.md)
**Update a Dataset**
**Operation ID:** `aig-config-update-dataset`

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
| 200 | Returns the updated Object |
| 400 | Input Validation Error |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
