# GET /api/v4/projects/{id}/repository/branches

**Resource:** [Branches](../resources/Branches.md)
**Get a project repository branches**
**Operation ID:** `getApiV4ProjectsIdRepositoryBranches`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `search` | query | string | No | Return list of branches matching the search criteria |
| `regex` | query | string | No | Return list of branches matching the regex |
| `sort` | query | enum: name_asc, updated_asc, updated_desc | No | Return list of branches sorted by the given field |
| `page_token` | query | string | No | Name of branch to start the pagination from |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | 404 Project Not Found |

**Success Response Schema:**

[APIEntitiesBranch](../schemas/APIEntitiesBranch/APIEntitiesBranch.md)

