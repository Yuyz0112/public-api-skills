# POST /api/v4/projects/{id}/repository_size

**Resource:** [Projects](../resources/Projects.md)
**Start a task to recalculate repository size for a project**
**Operation ID:** `postApiV4ProjectsIdRepositorySize`

This feature was introduced in GitLab 15.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Unauthenticated |

