# GET /api/v4/groups/{id}/clusters/{cluster_id}

**Resource:** [Clusters](../resources/Clusters.md)
**Get a single group cluster**
**Operation ID:** `getApiV4GroupsIdClustersClusterId`

This feature was introduced in GitLab 12.1. Gets a single group cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the group |
| `cluster_id` | path | integer | Yes | The cluster ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesClusterGroup](../schemas/APIEntitiesClusterGroup/APIEntitiesClusterGroup.md)

