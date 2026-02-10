# POST /api/v4/projects/{id}/share

**Resource:** [Projects](../resources/Projects.md)
**Share the project with a group**
**Operation ID:** `postApiV4ProjectsIdShare`

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
| 400 | Bad request |
| 403 | Unauthenticated |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProjectGroupLink](../schemas/APIEntitiesProjectGroupLink/APIEntitiesProjectGroupLink.md)

