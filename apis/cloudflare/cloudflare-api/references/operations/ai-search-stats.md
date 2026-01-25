# GET /accounts/{account_id}/ai-search/instances/{id}/stats

**Resource:** [AI Search Instances](../resources/AI-Search-Instances.md)
**Stats**
**Operation ID:** `ai-search-stats`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Use your AI Search ID. |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the AI Search stats. |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
