# GET /api/v4/projects/{id}/registry/repositories/{repository_id}/tags

**Resource:** [Container registry](../resources/Container-registry.md)
**List tags of a repository**
**Operation ID:** `getApiV4ProjectsIdRegistryRepositoriesRepositoryIdTags`

This feature was introduced in GitLab 11.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `repository_id` | path | integer | Yes | The ID of the repository |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not Found |
| 405 | Method Not Allowed |

**Success Response Schema:**

[APIEntitiesContainerRegistryTag](../schemas/APIEntitiesContainerRegistryTag/APIEntitiesContainerRegistryTag.md)

