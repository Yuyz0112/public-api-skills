# GET /accounts/{account_id}/ai-search/instances

**Resource:** [AI Search Instances](../resources/AI-Search-Instances.md)
**List instances.**
**Operation ID:** `ai-search-list-instances`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `search` | query | string | No | Search by id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List objects |
| 400 | Bad Request. |

## Security

- **api_token**
- **api_email**
- **api_key**
