# PUT /api/v4/admin/knowledge_graph/namespaces/{id}

**Resource:** [Knowledge graph](../resources/Knowledge-graph.md)
**Enable a namespace for Knowledge Graph**
**Operation ID:** `putApiV4AdminKnowledgeGraphNamespacesId`

This endpoint enables Knowledge Graph for a specific namespace

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the namespace |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad Request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesAiKnowledgeGraphEnabledNamespace](../schemas/APIEntitiesAiKnowledgeGraphEnabledNamespace/APIEntitiesAiKnowledgeGraphEnabledNamespace.md)

