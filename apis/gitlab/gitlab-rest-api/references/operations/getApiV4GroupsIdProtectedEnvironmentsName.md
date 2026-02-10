# GET /api/v4/groups/{id}/protected_environments/{name}

**Resource:** [Protected environments](../resources/Protected-environments.md)
**Get a single protected environment**
**Operation ID:** `getApiV4GroupsIdProtectedEnvironmentsName`

Gets a single protected environment. This feature was introduced in GitLab 14.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group maintained by the authenticated user |
| `name` | path | string | Yes | The deployment tier of the protected environment. One of `production`, `staging`, `testing`, `development`, or `other` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProtectedEnvironment](../schemas/APIEntitiesProtectedEnvironment/APIEntitiesProtectedEnvironment.md)

