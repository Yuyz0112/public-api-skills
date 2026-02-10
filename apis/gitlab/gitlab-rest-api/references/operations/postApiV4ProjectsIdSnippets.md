# POST /api/v4/projects/{id}/snippets

**Resource:** [Snippets](../resources/Snippets.md)
**Create a new project snippet**
**Operation ID:** `postApiV4ProjectsIdSnippets`

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
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesProjectSnippet](../schemas/APIEntitiesProjectSnippet/APIEntitiesProjectSnippet.md)

