# POST /api/v4/projects/{id}/repository/commits/authorize

**Resource:** [Commits](../resources/Commits.md)
**Authorize commits upload**
**Operation ID:** `postApiV4ProjectsIdRepositoryCommitsAuthorize`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

