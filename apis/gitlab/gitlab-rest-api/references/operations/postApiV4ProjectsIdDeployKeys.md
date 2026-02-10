# POST /api/v4/projects/{id}/deploy_keys

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Add deploy key**
**Operation ID:** `postApiV4ProjectsIdDeployKeys`

Creates a new deploy key for a project. If the deploy key already exists in another project, it's joined to the current project only if the original one is accessible by the same user.

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

[APIEntitiesDeployKeysProject](../schemas/APIEntitiesDeployKeysProject/APIEntitiesDeployKeysProject.md)

