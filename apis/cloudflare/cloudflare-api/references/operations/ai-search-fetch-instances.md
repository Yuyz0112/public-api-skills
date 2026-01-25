# GET /accounts/{account_id}/ai-search/instances/{id}

**Resource:** [AI Search Instances](../resources/AI-Search-Instances.md)
**Read instances.**
**Operation ID:** `ai-search-fetch-instances`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `id` | path | string | Yes | Use your AI Search ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a single object if found |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
