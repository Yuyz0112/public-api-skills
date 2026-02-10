# GET /api/v4/projects/{id}/snippets/{snippet_id}/raw

**Resource:** [Snippets](../resources/Snippets.md)
**Get a raw project snippet**
**Operation ID:** `getApiV4ProjectsIdSnippetsSnippetIdRaw`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `snippet_id` | path | integer | Yes | The ID of a project snippet |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProjectSnippet](../schemas/APIEntitiesProjectSnippet/APIEntitiesProjectSnippet.md)

