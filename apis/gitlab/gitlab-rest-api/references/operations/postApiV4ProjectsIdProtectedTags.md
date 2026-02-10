# POST /api/v4/projects/{id}/protected_tags

**Resource:** [Protected tags](../resources/Protected-tags.md)
**Protect a single tag or wildcard**
**Operation ID:** `postApiV4ProjectsIdProtectedTags`

This feature was introduced in GitLab 11.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 403 | Unauthenticated |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesProtectedTag](../schemas/APIEntitiesProtectedTag/APIEntitiesProtectedTag.md)

