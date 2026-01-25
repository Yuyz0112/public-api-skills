# GET /accounts/{account_id}/ai/models/schema

**Resource:** [Workers AI](../resources/Workers-AI.md)
**Get Model Schema**
**Operation ID:** `workers-ai-get-model-schema`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `model` | query | string | Yes | Model Name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Model Schema |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
