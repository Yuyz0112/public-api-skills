# GET /accounts/{account_id}/ai/finetunes/public

**Resource:** [Workers AI Finetune](../resources/Workers-AI-Finetune.md)
**List Public Finetunes**
**Operation ID:** `workers-ai-list-public-finetunes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `limit` | query | number | No | Pagination Limit |
| `offset` | query | number | No | Pagination Offset |
| `orderBy` | query | string | No | Order By Column Name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns all public finetunes |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
