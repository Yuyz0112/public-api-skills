# GET /api/v4/projects/{id}/protected_tags/{name}

**Resource:** [Protected tags](../resources/Protected-tags.md)
**Get a single protected tag**
**Operation ID:** `getApiV4ProjectsIdProtectedTagsName`

This feature was introduced in GitLab 11.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of the tag or wildcard |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProtectedTag](../schemas/APIEntitiesProtectedTag/APIEntitiesProtectedTag.md)

