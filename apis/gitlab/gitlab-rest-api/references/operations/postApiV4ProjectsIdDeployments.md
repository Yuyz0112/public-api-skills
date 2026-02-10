# POST /api/v4/projects/{id}/deployments

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Create a deployment**
**Operation ID:** `postApiV4ProjectsIdDeployments`

This feature was introduced in GitLab 12.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeploymentExtended](../schemas/APIEntitiesDeploymentExtended/APIEntitiesDeploymentExtended.md)

