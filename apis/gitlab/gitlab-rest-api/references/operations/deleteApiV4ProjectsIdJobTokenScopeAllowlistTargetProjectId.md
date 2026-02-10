# DELETE /api/v4/projects/{id}/job_token_scope/allowlist/{target_project_id}

**Resource:** [Projects job token scope](../resources/Projects-job-token-scope.md)
**Delete project from allowlist.**
**Operation ID:** `deleteApiV4ProjectsIdJobTokenScopeAllowlistTargetProjectId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | ID of user project |
| `target_project_id` | path | integer | Yes | ID of the project to be removed from the allowlist |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

