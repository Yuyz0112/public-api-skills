# GET /api/v4/projects/{id}/repository/commits

**Resource:** [Commits](../resources/Commits.md)
**Get a project repository commits**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommits`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `ref_name` | query | string | No | The name of a repository branch or tag, if not given the default branch is used |
| `since` | query | string (date-time) | No | Only commits after or on this date will be returned |
| `until` | query | string (date-time) | No | Only commits before or on this date will be returned |
| `path` | query | string | No | The file path |
| `author` | query | string | No | Search commits by commit author |
| `all` | query | boolean | No | Every commit will be returned |
| `with_stats` | query | boolean | No | Stats about each commit will be added to the response |
| `first_parent` | query | boolean | No | Only include the first parent of merges |
| `order` | query | enum: default, topo | No | List commits in order |
| `trailers` | query | boolean | No | Parse and include Git trailers for every commit |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCommit](../schemas/APIEntitiesCommit/APIEntitiesCommit.md)

