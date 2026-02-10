# DELETE /api/v4/admin/zoekt/shards/{node_id}/indexed_namespaces/{namespace_id}

**Resource:** [Code search](../resources/Code-search.md)
**Remove a namespace from a node for Zoekt indexing**
**Operation ID:** `deleteApiV4AdminZoektShardsNodeIdIndexedNamespacesNamespaceId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `node_id` | path | integer | Yes | The id of the Search::Zoekt::Node |
| `namespace_id` | path | integer | Yes | The id of the namespace you want to remove from this node |

## Responses

| Status | Description |
|--------|-------------|
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

