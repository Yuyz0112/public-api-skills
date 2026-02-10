# GET /api/v4/groups/{id}/clusters

**Resource:** [Clusters](../resources/Clusters.md)
**List group clusters**
**Operation ID:** `getApiV4GroupsIdClusters`

This feature was introduced in GitLab 12.1. Returns a list of group clusters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesCluster](../schemas/APIEntitiesCluster/APIEntitiesCluster.md)

