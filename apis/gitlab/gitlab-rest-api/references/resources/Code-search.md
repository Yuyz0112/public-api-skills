# Code search

Operations related to code search.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| PUT | `/api/v4/admin/zoekt/projects/{project_id}/index` | Triggers indexing for the specified project | [View](../operations/putApiV4AdminZoektProjectsProjectIdIndex.md) |
| PATCH | `/api/v4/admin/zoekt/namespaces/{id}` | Update the number of replicas override for an enabled namespace | [View](../operations/patchApiV4AdminZoektNamespacesId.md) |
| GET | `/api/v4/admin/zoekt/shards` | Get all the Zoekt nodes | [View](../operations/getApiV4AdminZoektShards.md) |
| GET | `/api/v4/admin/zoekt/shards/{node_id}/indexed_namespaces` | Get all the indexed namespaces for this node | [View](../operations/getApiV4AdminZoektShardsNodeIdIndexedNamespaces.md) |
| PUT | `/api/v4/admin/zoekt/shards/{node_id}/indexed_namespaces/{namespace_id}` | Add a namespace to a node for Zoekt indexing | [View](../operations/putApiV4AdminZoektShardsNodeIdIndexedNamespacesNamespaceId.md) |
| DELETE | `/api/v4/admin/zoekt/shards/{node_id}/indexed_namespaces/{namespace_id}` | Remove a namespace from a node for Zoekt indexing | [View](../operations/deleteApiV4AdminZoektShardsNodeIdIndexedNamespacesNamespaceId.md) |
