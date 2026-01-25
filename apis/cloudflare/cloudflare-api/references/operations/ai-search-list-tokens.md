# GET /accounts/{account_id}/ai-search/tokens

**Resource:** [AI Search Tokens](../resources/AI-Search-Tokens.md)
**List tokens.**
**Operation ID:** `ai-search-list-tokens`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List objects |
| 400 | Bad Request. |

## Security

- **api_token**
- **api_email**
- **api_key**
