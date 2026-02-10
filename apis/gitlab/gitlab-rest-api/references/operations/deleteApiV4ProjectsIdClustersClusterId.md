# DELETE /api/v4/projects/{id}/clusters/{cluster_id}

**Resource:** [Clusters](../resources/Clusters.md)
**Delete project cluster**
**Operation ID:** `deleteApiV4ProjectsIdClustersClusterId`

This feature was introduced in GitLab 11.7. Deletes an existing project cluster. Does not remove existing resources within the connected Kubernetes cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `cluster_id` | path | integer | Yes | The Cluster ID |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 404 | Not found |

