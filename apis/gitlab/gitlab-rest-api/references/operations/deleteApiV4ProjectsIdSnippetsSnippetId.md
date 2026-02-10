# DELETE /api/v4/projects/{id}/snippets/{snippet_id}

**Resource:** [Snippets](../resources/Snippets.md)
**Delete a project snippet**
**Operation ID:** `deleteApiV4ProjectsIdSnippetsSnippetId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `snippet_id` | path | integer | Yes | The ID of a project snippet |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Validation error |
| 404 | Not found |

