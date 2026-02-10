# GET /api/v4/users/{user_id}/contributed_projects

**Resource:** [Projects](../resources/Projects.md)
**Get projects that a user has contributed to**
**Operation ID:** `getApiV4UsersUserIdContributedProjects`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | string | Yes | The ID or username of the user |
| `order_by` | query | enum: id, name, path... | No | Return projects ordered by field. storage_size, repository_size, wiki_size, packages_size are only available to admins. Similarity is available when searching and is limited to projects the user has access to. |
| `sort` | query | enum: asc, desc | No | Return projects sorted in ascending and descending order |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `simple` | query | boolean | No | Return only the ID, URL, name, and path of each project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | 404 User Not Found |

**Success Response Schema:**

[APIEntitiesBasicProjectDetails](../schemas/APIEntitiesBasicProjectDetails/APIEntitiesBasicProjectDetails.md)

