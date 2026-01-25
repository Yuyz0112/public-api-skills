# GET /accounts/{account_id}/autorag/rags/{id}/files

**Resource:** [AutoRAG RAG](../resources/AutoRAG-RAG.md)
**Files**
**Operation ID:** `autorag-config-files`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | rag id |
| `account_id` | path | string | Yes |  |
| `page` | query | integer | No |  |
| `per_page` | query | integer | No |  |
| `search` | query | string | No |  |
| `status` | query | enum: completed, queued, running... | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the AI Search files |
| 404 | autorag_not_found |
| 503 | unable_to_connect_to_autorag |

## Security

- **api_token**
- **api_email**
- **api_key**
