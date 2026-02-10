# GET /api/v4/projects/{id}/deploy_tokens/{token_id}

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Get a project deploy token**
**Operation ID:** `getApiV4ProjectsIdDeployTokensTokenId`

Get a single project's deploy token by ID. This feature was introduced in GitLab 14.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `token_id` | path | integer | Yes | The ID of the deploy token |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeployToken](../schemas/APIEntitiesDeployToken/APIEntitiesDeployToken.md)

