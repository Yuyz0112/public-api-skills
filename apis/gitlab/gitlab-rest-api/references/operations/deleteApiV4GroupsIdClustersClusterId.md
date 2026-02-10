# DELETE /api/v4/groups/{id}/clusters/{cluster_id}

**Resource:** [Clusters](../resources/Clusters.md)
**Delete group cluster**
**Operation ID:** `deleteApiV4GroupsIdClustersClusterId`

This feature was introduced in GitLab 12.1. Deletes an existing group cluster. Does not remove existing resources within the connected Kubernetes cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the group |
| `cluster_id` | path | integer | Yes | The Cluster ID |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 404 | Not found |

