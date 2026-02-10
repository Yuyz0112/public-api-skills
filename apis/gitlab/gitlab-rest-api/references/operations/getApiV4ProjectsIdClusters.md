# GET /api/v4/projects/{id}/clusters

**Resource:** [Clusters](../resources/Clusters.md)
**List project clusters**
**Operation ID:** `getApiV4ProjectsIdClusters`

This feature was introduced in GitLab 11.7. Returns a list of project clusters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesCluster](../schemas/APIEntitiesCluster/APIEntitiesCluster.md)

