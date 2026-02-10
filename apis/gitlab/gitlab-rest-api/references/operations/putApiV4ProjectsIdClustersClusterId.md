# PUT /api/v4/projects/{id}/clusters/{cluster_id}

**Resource:** [Clusters](../resources/Clusters.md)
**Edit project cluster**
**Operation ID:** `putApiV4ProjectsIdClustersClusterId`

This feature was introduced in GitLab 11.7. Updates an existing project cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
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

[APIEntitiesClusterProject](../schemas/APIEntitiesClusterProject/APIEntitiesClusterProject.md)

