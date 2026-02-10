# GET /api/v4/projects/{id}/repository/tree

**Resource:** [Repositories](../resources/Repositories.md)
**Get a project repository tree**
**Operation ID:** `getApiV4ProjectsIdRepositoryTree`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `ref` | query | string | No | The name of a repository branch or tag, if not given the default branch is used |
| `path` | query | string | No | The path of the tree |
| `recursive` | query | boolean | No | Used to get a recursive tree |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `pagination` | query | enum: legacy, keyset, none | No | Specify the pagination method ("none" is only valid if "recursive" is true) |
| `page_token` | query | string | No | Record from which to start the keyset pagination |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesTreeObject](../schemas/APIEntitiesTreeObject/APIEntitiesTreeObject.md)

