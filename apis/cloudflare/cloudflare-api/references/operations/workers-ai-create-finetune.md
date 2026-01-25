# POST /accounts/{account_id}/ai/finetunes

**Resource:** [Workers AI Finetune](../resources/Workers-AI-Finetune.md)
**Create a new Finetune**
**Operation ID:** `workers-ai-create-finetune`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the created finetune |
| 400 | Finetune creation failed |

## Security

- **api_token**
- **api_email**
- **api_key**
