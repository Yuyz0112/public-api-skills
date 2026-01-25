# GET /accounts/{account_id}/ai-search/instances/{id}/items

**Resource:** [AI Search Instances Items](../resources/AI-Search-Instances-Items.md)
**Items List.**
**Operation ID:** `ai-search-instance-list-items`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Use your AI Search ID. |
| `account_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `search` | query | string | No |  |
| `status` | query | enum: queued, running, completed... | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the AI Search items. |
| 404 | Not Found |
| 500 | Internal Error. |

## Security

- **api_token**
- **api_email**
- **api_key**
