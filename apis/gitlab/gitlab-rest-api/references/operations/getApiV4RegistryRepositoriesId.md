# GET /api/v4/registry/repositories/{id}

**Resource:** [Container registry](../resources/Container-registry.md)
**Get a container repository**
**Operation ID:** `getApiV4RegistryRepositoriesId`

This feature was introduced in GitLab 13.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID of the repository |
| `tags` | query | boolean | No | Determines if tags should be included |
| `tags_count` | query | boolean | No | Determines if the tags count should be included |
| `size` | query | boolean | No | Determines if the size should be included |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Repository Not Found |

**Success Response Schema:**

[APIEntitiesContainerRegistryRepository](../schemas/APIEntitiesContainerRegistryRepository/APIEntitiesContainerRegistryRepository.md)

