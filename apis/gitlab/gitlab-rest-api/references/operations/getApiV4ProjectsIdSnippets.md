# GET /api/v4/projects/{id}/snippets

**Resource:** [Snippets](../resources/Snippets.md)
**Get all project snippets**
**Operation ID:** `getApiV4ProjectsIdSnippets`

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
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProjectSnippet](../schemas/APIEntitiesProjectSnippet/APIEntitiesProjectSnippet.md)

