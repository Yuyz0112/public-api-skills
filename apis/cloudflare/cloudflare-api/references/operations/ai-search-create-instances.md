# POST /accounts/{account_id}/ai-search/instances

**Resource:** [AI Search Instances](../resources/AI-Search-Instances.md)
**Create new instances.**
**Operation ID:** `ai-search-create-instances`

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
