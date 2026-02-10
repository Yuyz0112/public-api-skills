# GET /api/v4/projects/{id}/starrers

**Resource:** [Projects](../resources/Projects.md)
**Get the users who starred a project**
**Operation ID:** `getApiV4ProjectsIdStarrers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `search` | query | string | No | Return list of users matching the search criteria |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesUserBasic](../schemas/APIEntitiesUserBasic/APIEntitiesUserBasic.md)

