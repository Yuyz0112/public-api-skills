# GET /api/v4/projects/{id}/registry/repositories/{repository_id}/tags/{tag_name}

**Resource:** [Container registry](../resources/Container-registry.md)
**Get details about a repository tag**
**Operation ID:** `getApiV4ProjectsIdRegistryRepositoriesRepositoryIdTagsTagName`

This feature was introduced in GitLab 11.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `repository_id` | path | integer | Yes | The ID of the repository |
| `tag_name` | path | string | Yes | The name of the tag |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesContainerRegistryTagDetails](../schemas/APIEntitiesContainerRegistryTagDetails/APIEntitiesContainerRegistryTagDetails.md)

