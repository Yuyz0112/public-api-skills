# GET /accounts/{account_id}/ai/finetunes

**Resource:** [Workers AI Finetune](../resources/Workers-AI-Finetune.md)
**List Finetunes**
**Operation ID:** `workers-ai-list-finetunes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns all finetunes |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
