# GET /api/v4/admin/clusters/{cluster_id}

**Resource:** [Clusters](../resources/Clusters.md)
**Get a single instance cluster**
**Operation ID:** `getApiV4AdminClustersClusterId`

This feature was introduced in GitLab 13.2. Returns a single instance cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cluster_id` | path | integer | Yes | The cluster ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCluster](../schemas/APIEntitiesCluster/APIEntitiesCluster.md)

