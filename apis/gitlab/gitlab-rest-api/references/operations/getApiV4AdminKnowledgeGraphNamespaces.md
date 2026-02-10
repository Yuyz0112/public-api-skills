# GET /api/v4/admin/knowledge_graph/namespaces

**Resource:** [Knowledge graph](../resources/Knowledge-graph.md)
**Get all enabled namespaces for Knowledge Graph**
**Operation ID:** `getApiV4AdminKnowledgeGraphNamespaces`

This endpoint retrieves all namespaces that have Knowledge Graph enabled

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad Request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |

**Success Response Schema:**

[APIEntitiesAiKnowledgeGraphEnabledNamespace](../schemas/APIEntitiesAiKnowledgeGraphEnabledNamespace/APIEntitiesAiKnowledgeGraphEnabledNamespace.md)

