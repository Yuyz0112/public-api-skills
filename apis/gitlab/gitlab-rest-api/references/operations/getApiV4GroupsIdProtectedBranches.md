# GET /api/v4/groups/{id}/protected_branches

**Resource:** [Protected branches](../resources/Protected-branches.md)
**Get a group's protected branches**
**Operation ID:** `getApiV4GroupsIdProtectedBranches`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `search` | query | string | No | Search for a protected branch by name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 404 | 404 Group Not Found |

**Success Response Schema:**

[APIEntitiesGroupProtectedBranch](../schemas/APIEntitiesGroupProtectedBranch/APIEntitiesGroupProtectedBranch.md)

