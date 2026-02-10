# POST /api/v4/groups/{id}/protected_environments

**Resource:** [Protected environments](../resources/Protected-environments.md)
**Protect a single environment**
**Operation ID:** `postApiV4GroupsIdProtectedEnvironments`

Protects a single environment. This feature was introduced in GitLab 14.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group maintained by the authenticated user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 404 | Not found |
| 409 | Conflict |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesProtectedEnvironment](../schemas/APIEntitiesProtectedEnvironment/APIEntitiesProtectedEnvironment.md)

