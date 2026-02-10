# DELETE /api/v4/admin/knowledge_graph/namespaces/{id}

**Resource:** [Knowledge graph](../resources/Knowledge-graph.md)
**Disable a namespace for Knowledge Graph**
**Operation ID:** `deleteApiV4AdminKnowledgeGraphNamespacesId`

This endpoint disables Knowledge Graph for a specific namespace

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the namespace |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | 400 Bad Request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

