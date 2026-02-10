# PUT /api/v4/admin/clusters/{cluster_id}

**Resource:** [Clusters](../resources/Clusters.md)
**Edit instance cluster**
**Operation ID:** `putApiV4AdminClustersClusterId`

This feature was introduced in GitLab 13.2. Updates an existing instance cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cluster_id` | path | integer | Yes | The cluster ID |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Validation error |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCluster](../schemas/APIEntitiesCluster/APIEntitiesCluster.md)

