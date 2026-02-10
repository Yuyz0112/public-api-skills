# PUT /api/v4/groups/{id}/protected_environments/{name}

**Resource:** [Protected environments](../resources/Protected-environments.md)
**Update a protected environment**
**Operation ID:** `putApiV4GroupsIdProtectedEnvironmentsName`

Updates a single environment. This feature was introduced in GitLab 15.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group maintained by the authenticated user |
| `name` | path | string | Yes | The deployment tier of the protected environment. One of production, staging, testing, development, or other |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 |  |
| 422 |  |

**Success Response Schema:**

[APIEntitiesProtectedEnvironment](../schemas/APIEntitiesProtectedEnvironment/APIEntitiesProtectedEnvironment.md)

