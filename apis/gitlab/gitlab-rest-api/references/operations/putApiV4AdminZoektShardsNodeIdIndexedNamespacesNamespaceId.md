# PUT /api/v4/admin/zoekt/shards/{node_id}/indexed_namespaces/{namespace_id}

**Resource:** [Code search](../resources/Code-search.md)
**Add a namespace to a node for Zoekt indexing**
**Operation ID:** `putApiV4AdminZoektShardsNodeIdIndexedNamespacesNamespaceId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `node_id` | path | integer | Yes | The id of the Search::Zoekt::Node |
| `namespace_id` | path | integer | Yes | The id of the namespace you want to index in this node |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesSearchZoektIndexedNamespace](../schemas/APIEntitiesSearchZoektIndexedNamespace/APIEntitiesSearchZoektIndexedNamespace.md)

