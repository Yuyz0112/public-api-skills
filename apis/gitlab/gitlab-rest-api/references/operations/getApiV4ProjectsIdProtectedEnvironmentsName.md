# GET /api/v4/projects/{id}/protected_environments/{name}

**Resource:** [Protected environments](../resources/Protected-environments.md)
**Get a single protected environment**
**Operation ID:** `getApiV4ProjectsIdProtectedEnvironmentsName`

Gets a single protected environment. This feature was introduced in GitLab 12.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `name` | path | string | Yes | The name of the protected environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProtectedEnvironment](../schemas/APIEntitiesProtectedEnvironment/APIEntitiesProtectedEnvironment.md)

