# DELETE /api/v4/projects/{id}/deployments/{deployment_id}

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Delete a specific deployment**
**Operation ID:** `deleteApiV4ProjectsIdDeploymentsDeploymentId`

Delete a specific deployment that is not currently the last deployment for an environment or in a running state. This feature was introduced in GitLab 15.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `deployment_id` | path | integer | Yes | The ID of the deployment |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Deployment destroyed |
| 400 | "Cannot destroy running deployment" or "Deployment currently deployed to environment" |
| 403 | Forbidden |

