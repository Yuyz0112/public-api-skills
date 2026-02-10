# POST /api/v4/admin/clusters/add

**Resource:** [Clusters](../resources/Clusters.md)
**Add existing instance cluster**
**Operation ID:** `postApiV4AdminClustersAdd`

This feature was introduced in GitLab 13.2. Adds an existing Kubernetes instance cluster.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Validation error |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCluster](../schemas/APIEntitiesCluster/APIEntitiesCluster.md)

