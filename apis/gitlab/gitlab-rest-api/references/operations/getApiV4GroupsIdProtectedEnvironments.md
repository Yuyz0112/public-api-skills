# GET /api/v4/groups/{id}/protected_environments

**Resource:** [Protected environments](../resources/Protected-environments.md)
**List group-level protected environments**
**Operation ID:** `getApiV4GroupsIdProtectedEnvironments`

Gets a list of protected environments from a group. This feature was introduced in GitLab 14.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group maintained by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProtectedEnvironment](../schemas/APIEntitiesProtectedEnvironment/APIEntitiesProtectedEnvironment.md)

