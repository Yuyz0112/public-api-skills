# POST /api/v4/groups/{id}/clusters/user

**Resource:** [Clusters](../resources/Clusters.md)
**Add existing cluster to group**
**Operation ID:** `postApiV4GroupsIdClustersUser`

This feature was introduced in GitLab 12.1. Adds an existing Kubernetes cluster to the group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the group |

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

[APIEntitiesClusterGroup](../schemas/APIEntitiesClusterGroup/APIEntitiesClusterGroup.md)

