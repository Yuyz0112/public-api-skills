# GET /accounts/{account_id}/ai/tasks/search

**Resource:** [Workers AI](../resources/Workers-AI.md)
**Task Search**
**Operation ID:** `workers-ai-search-task`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of tasks |
| 404 | Object not found |

## Security

- **api_token**
- **api_email**
- **api_key**
