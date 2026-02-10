# DELETE /api/v4/projects/{id}/repository/tags/{tag_name}

**Resource:** [Tags](../resources/Tags.md)
**Delete a repository tag**
**Operation ID:** `deleteApiV4ProjectsIdRepositoryTagsTagName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The name of the tag |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 403 | Unauthenticated |
| 404 | Not found |
| 412 | Precondition failed |

