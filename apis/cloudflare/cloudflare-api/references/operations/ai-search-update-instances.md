# PUT /accounts/{account_id}/ai-search/instances/{id}

**Resource:** [AI Search Instances](../resources/AI-Search-Instances.md)
**Update instances.**
**Operation ID:** `ai-search-update-instances`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `id` | path | string | Yes | Use your AI Search ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated Object |
| 400 | Input Validation Error |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
