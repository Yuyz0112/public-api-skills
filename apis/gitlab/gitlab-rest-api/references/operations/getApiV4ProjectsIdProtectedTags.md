# GET /api/v4/projects/{id}/protected_tags

**Resource:** [Protected tags](../resources/Protected-tags.md)
**Get a project's protected tags**
**Operation ID:** `getApiV4ProjectsIdProtectedTags`

This feature was introduced in GitLab 11.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProtectedTag](../schemas/APIEntitiesProtectedTag/APIEntitiesProtectedTag.md)

