# PUT /api/v4/projects/{id}/deployments/{deployment_id}

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Update a deployment**
**Operation ID:** `putApiV4ProjectsIdDeploymentsDeploymentId`

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
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeploymentExtended](../schemas/APIEntitiesDeploymentExtended/APIEntitiesDeploymentExtended.md)

