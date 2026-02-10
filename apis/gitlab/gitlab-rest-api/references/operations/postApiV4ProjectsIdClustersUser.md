# POST /api/v4/projects/{id}/clusters/user

**Resource:** [Clusters](../resources/Clusters.md)
**Add existing cluster to project**
**Operation ID:** `postApiV4ProjectsIdClustersUser`

This feature was introduced in GitLab 11.7. Adds an existing Kubernetes cluster to the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

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

[APIEntitiesClusterProject](../schemas/APIEntitiesClusterProject/APIEntitiesClusterProject.md)

