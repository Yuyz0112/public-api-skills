# PATCH /accounts/{account_id}/autorag/rags/{id}/sync

**Resource:** [AutoRAG RAG](../resources/AutoRAG-RAG.md)
**Sync**
**Operation ID:** `autorag-config-sync`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | rag id |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the autorag sync status |
| 400 | autorag_is_paused |
| 404 | autorag_not_found |
| 429 | sync_in_cooldown |
| 503 | unable_to_connect_to_autorag |

## Security

- **api_token**
- **api_email**
- **api_key**
