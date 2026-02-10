# POST /api/v4/projects/{id}/repository/tags

**Resource:** [Tags](../resources/Tags.md)
**Create a new repository tag**
**Operation ID:** `postApiV4ProjectsIdRepositoryTags`

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

[APIEntitiesTag](../schemas/APIEntitiesTag/APIEntitiesTag.md)

