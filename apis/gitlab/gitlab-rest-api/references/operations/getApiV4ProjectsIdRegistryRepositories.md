# GET /api/v4/projects/{id}/registry/repositories

**Resource:** [Container registry](../resources/Container-registry.md)
**List container repositories within a project**
**Operation ID:** `getApiV4ProjectsIdRegistryRepositories`

This feature was introduced in GitLab 11.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `tags` | query | boolean | No | Determines if tags should be included |
| `tags_count` | query | boolean | No | Determines if the tags count should be included |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesContainerRegistryRepository](../schemas/APIEntitiesContainerRegistryRepository/APIEntitiesContainerRegistryRepository.md)

