# GET /api/v4/projects/{id}/deployments/{deployment_id}

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Get a specific deployment**
**Operation ID:** `getApiV4ProjectsIdDeploymentsDeploymentId`

This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `deployment_id` | path | integer | Yes | The ID of the deployment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeploymentExtended](../schemas/APIEntitiesDeploymentExtended/APIEntitiesDeploymentExtended.md)

