# DELETE /api/v4/snippets/{id}

**Resource:** [Snippets](../resources/Snippets.md)
**Remove snippet**
**Operation ID:** `deleteApiV4SnippetsId`

This feature was introduced in GitLab 8.15.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a snippet |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Validation error |
| 404 | Not found |

