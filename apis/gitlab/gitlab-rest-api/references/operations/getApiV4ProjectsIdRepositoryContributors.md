# GET /api/v4/projects/{id}/repository/contributors

**Resource:** [Repositories](../resources/Repositories.md)
**Get repository contributors**
**Operation ID:** `getApiV4ProjectsIdRepositoryContributors`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `ref` | query | string | No | The name of a repository branch or tag, if not given the default branch is used |
| `order_by` | query | enum: email, name, commits | No | Return contributors ordered by `name` or `email` or `commits` |
| `sort` | query | enum: asc, desc | No | Sort by asc (ascending) or desc (descending) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesContributor](../schemas/APIEntitiesContributor/APIEntitiesContributor.md)

