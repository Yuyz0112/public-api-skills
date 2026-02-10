# GET /api/v4/groups/{id}/registry/repositories

**Resource:** [Container registry](../resources/Container-registry.md)
**List registry repositories within a group**
**Operation ID:** `getApiV4GroupsIdRegistryRepositories`

Get a list of registry repositories in a group. This feature was introduced in GitLab 12.2.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group accessible by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Group Not Found |

**Success Response Schema:**

[APIEntitiesContainerRegistryRepository](../schemas/APIEntitiesContainerRegistryRepository/APIEntitiesContainerRegistryRepository.md)

