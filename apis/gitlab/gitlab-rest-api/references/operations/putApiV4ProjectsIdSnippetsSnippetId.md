# PUT /api/v4/projects/{id}/snippets/{snippet_id}

**Resource:** [Snippets](../resources/Snippets.md)
**Update an existing project snippet**
**Operation ID:** `putApiV4ProjectsIdSnippetsSnippetId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `snippet_id` | path | integer | Yes | The ID of a project snippet |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesProjectSnippet](../schemas/APIEntitiesProjectSnippet/APIEntitiesProjectSnippet.md)

