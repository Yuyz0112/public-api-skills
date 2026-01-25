# POST /accounts/{account_id}/ai/finetunes/{finetune_id}/finetune-assets

**Resource:** [Workers AI Finetune](../resources/Workers-AI-Finetune.md)
**Upload a Finetune Asset**
**Operation ID:** `workers-ai-upload-finetune-asset`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `finetune_id` | path | string | Yes |  |

## Request Body

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns successfully if finetunes were uploaded |
| 400 | Finetune creation failed |

## Security

- **api_token**
- **api_email**
- **api_key**
