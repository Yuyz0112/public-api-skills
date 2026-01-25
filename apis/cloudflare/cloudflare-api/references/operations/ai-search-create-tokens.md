# POST /accounts/{account_id}/ai-search/tokens

**Resource:** [AI Search Tokens](../resources/AI-Search-Tokens.md)
**Create new tokens.**
**Operation ID:** `ai-search-create-tokens`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returns the created Object |
| 400 | Input Validation Error |

## Security

- **api_token**
- **api_email**
- **api_key**
