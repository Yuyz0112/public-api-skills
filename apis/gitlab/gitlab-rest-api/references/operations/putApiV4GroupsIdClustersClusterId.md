# PUT /api/v4/groups/{id}/clusters/{cluster_id}

**Resource:** [Clusters](../resources/Clusters.md)
**Edit group cluster**
**Operation ID:** `putApiV4GroupsIdClustersClusterId`

This feature was introduced in GitLab 12.1. Updates an existing group cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the group |
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

[APIEntitiesClusterGroup](../schemas/APIEntitiesClusterGroup/APIEntitiesClusterGroup.md)

