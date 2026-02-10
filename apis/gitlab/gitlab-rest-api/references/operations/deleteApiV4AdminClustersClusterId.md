# DELETE /api/v4/admin/clusters/{cluster_id}

**Resource:** [Clusters](../resources/Clusters.md)
**Delete instance cluster**
**Operation ID:** `deleteApiV4AdminClustersClusterId`

This feature was introduced in GitLab 13.2. Deletes an existing instance cluster. Does not remove existing resources within the connected Kubernetes cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cluster_id` | path | integer | Yes | The cluster ID |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 404 | Not found |

