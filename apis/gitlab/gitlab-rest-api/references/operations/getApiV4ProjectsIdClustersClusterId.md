# GET /api/v4/projects/{id}/clusters/{cluster_id}

**Resource:** [Clusters](../resources/Clusters.md)
**Get a single project cluster**
**Operation ID:** `getApiV4ProjectsIdClustersClusterId`

This feature was introduced in GitLab 11.7. Gets a single project cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `cluster_id` | path | integer | Yes | The cluster ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesClusterProject](../schemas/APIEntitiesClusterProject/APIEntitiesClusterProject.md)

