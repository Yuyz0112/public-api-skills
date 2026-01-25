# GET /accounts/{account_id}/ai/models/search

**Resource:** [Workers AI](../resources/Workers-AI.md)
**Model Search**
**Operation ID:** `workers-ai-search-model`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `per_page` | query | integer | No |  |
| `page` | query | integer | No |  |
| `task` | query | string | No | Filter by Task Name |
| `author` | query | string | No | Filter by Author |
| `source` | query | number | No | Filter by Source Id |
| `hide_experimental` | query | boolean | No | Filter to hide experimental models |
| `search` | query | string | No | Search |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of models |
| 404 | Object not found |

## Security

- **api_token**
- **api_email**
- **api_key**
