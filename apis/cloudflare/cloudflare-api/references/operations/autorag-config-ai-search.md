# POST /accounts/{account_id}/autorag/rags/{id}/ai-search

**Resource:** [AutoRAG RAG Search](../resources/AutoRAG-RAG-Search.md)
**AI Search**
**Operation ID:** `autorag-config-ai-search`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | rag id |
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the log details |
| 404 | Not Found |

## Security

- **api_token**
- **api_email**
- **api_key**
