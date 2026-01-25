# GET /accounts/{account_id}/ai-search/instances/{id}/items/{item_id}

**Resource:** [AI Search Instances Items](../resources/AI-Search-Instances-Items.md)
**Get Items.**
**Operation ID:** `ai-search-instance-get-item`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Use your AI Search ID. |
| `item_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a AI Search Item detail. |
| 400 | Bad Request. |
| 500 | Internal Error. |

## Security

- **api_token**
- **api_email**
- **api_key**
