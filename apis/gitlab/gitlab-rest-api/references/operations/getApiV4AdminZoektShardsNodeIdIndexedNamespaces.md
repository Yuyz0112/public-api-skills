# GET /api/v4/admin/zoekt/shards/{node_id}/indexed_namespaces

**Resource:** [Code search](../resources/Code-search.md)
**Get all the indexed namespaces for this node**
**Operation ID:** `getApiV4AdminZoektShardsNodeIdIndexedNamespaces`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `node_id` | path | integer | Yes | The id of the Search::Zoekt::Node |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesSearchZoektIndexedNamespace](../schemas/APIEntitiesSearchZoektIndexedNamespace/APIEntitiesSearchZoektIndexedNamespace.md)

