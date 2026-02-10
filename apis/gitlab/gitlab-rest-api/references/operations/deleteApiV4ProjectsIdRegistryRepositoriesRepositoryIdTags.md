# DELETE /api/v4/projects/{id}/registry/repositories/{repository_id}/tags

**Resource:** [Container registry](../resources/Container-registry.md)
**Delete repository tags (in bulk)**
**Operation ID:** `deleteApiV4ProjectsIdRegistryRepositoriesRepositoryIdTags`

This feature was introduced in GitLab 11.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `repository_id` | path | integer | Yes | The ID of the repository |
| `name_regex_delete` | query | string | No | The tag name regexp to delete, specify .* to delete all |
| `name_regex` | query | string | No | The tag name regexp to delete, specify .* to delete all |
| `name_regex_keep` | query | string | No | The tag name regexp to retain |
| `keep_n` | query | integer | No | Keep n of latest tags with matching name |
| `older_than` | query | string | No | Delete older than: 1h, 1d, 1month |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Not Found |

