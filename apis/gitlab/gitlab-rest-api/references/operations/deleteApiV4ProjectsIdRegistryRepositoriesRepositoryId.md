# DELETE /api/v4/projects/{id}/registry/repositories/{repository_id}

**Resource:** [Container registry](../resources/Container-registry.md)
**Delete repository**
**Operation ID:** `deleteApiV4ProjectsIdRegistryRepositoriesRepositoryId`

This feature was introduced in GitLab 11.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `repository_id` | path | integer | Yes | The ID of the repository |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 404 | Not Found |

