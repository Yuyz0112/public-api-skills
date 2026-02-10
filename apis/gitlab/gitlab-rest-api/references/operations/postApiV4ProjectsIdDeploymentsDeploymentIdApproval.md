# POST /api/v4/projects/{id}/deployments/{deployment_id}/approval

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Approve or reject a blocked deployment**
**Operation ID:** `postApiV4ProjectsIdDeploymentsDeploymentIdApproval`

This feature was introduced in GitLab 14.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `deployment_id` | path | integer | Yes | The ID of the deployment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesDeploymentsApproval](../schemas/APIEntitiesDeploymentsApproval/APIEntitiesDeploymentsApproval.md)

