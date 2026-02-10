# GET /api/v4/projects/{id}/snippets/{snippet_id}/files/{ref}/{file_path}/raw

**Resource:** [Snippets](../resources/Snippets.md)
**Get raw project snippet file contents from the repository**
**Operation ID:** `getApiV4ProjectsIdSnippetsSnippetIdFilesRefFilePathRaw`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_path` | path | string | Yes | The URL-encoded path to the file, like lib%2Fclass%2Erb |
| `ref` | path | string | Yes | The name of branch, tag or commit |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProjectSnippet](../schemas/APIEntitiesProjectSnippet/APIEntitiesProjectSnippet.md)

