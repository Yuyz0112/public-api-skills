# GET /accounts/{account_id}/ai/authors/search

**Resource:** [Workers AI](../resources/Workers-AI.md)
**Author Search**
**Operation ID:** `workers-ai-search-author`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a list of authors |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**
