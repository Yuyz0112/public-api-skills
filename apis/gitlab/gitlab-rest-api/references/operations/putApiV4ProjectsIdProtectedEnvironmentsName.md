# PUT /api/v4/projects/{id}/protected_environments/{name}

**Resource:** [Protected environments](../resources/Protected-environments.md)
**Update a protected environment**
**Operation ID:** `putApiV4ProjectsIdProtectedEnvironmentsName`

Updates a single environment. This feature was introduced in GitLab 15.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `name` | path | string | Yes | The name of the environment |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesProtectedEnvironment](../schemas/APIEntitiesProtectedEnvironment/APIEntitiesProtectedEnvironment.md)

