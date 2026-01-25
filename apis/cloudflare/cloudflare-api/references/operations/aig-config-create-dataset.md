# POST /accounts/{account_id}/ai-gateway/gateways/{gateway_id}/datasets

**Resource:** [AI Gateway Datasets](../resources/AI-Gateway-Datasets.md)
**Create a new Dataset**
**Operation ID:** `aig-config-create-dataset`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `gateway_id` | path | string | Yes |  |
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
