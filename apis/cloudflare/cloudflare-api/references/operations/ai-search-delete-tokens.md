# DELETE /accounts/{account_id}/ai-search/tokens/{id}

**Resource:** [AI Search Tokens](../resources/AI-Search-Tokens.md)
**Delete tokens.**
**Operation ID:** `ai-search-delete-tokens`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the Object if it was successfully deleted |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
