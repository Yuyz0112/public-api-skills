# Projects job token scope

Operations related to projects job token scope.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/job_token_scope` | Fetch CI_JOB_TOKEN access settings. | [View](../operations/getApiV4ProjectsIdJobTokenScope.md) |
| PATCH | `/api/v4/projects/{id}/job_token_scope` | Patch CI_JOB_TOKEN access settings. | [View](../operations/patchApiV4ProjectsIdJobTokenScope.md) |
| GET | `/api/v4/projects/{id}/job_token_scope/allowlist` | Fetch project inbound allowlist for CI_JOB_TOKEN access settings. | [View](../operations/getApiV4ProjectsIdJobTokenScopeAllowlist.md) |
| POST | `/api/v4/projects/{id}/job_token_scope/allowlist` | Add target project to allowlist. | [View](../operations/postApiV4ProjectsIdJobTokenScopeAllowlist.md) |
| GET | `/api/v4/projects/{id}/job_token_scope/groups_allowlist` | Fetch project groups allowlist for CI_JOB_TOKEN access settings. | [View](../operations/getApiV4ProjectsIdJobTokenScopeGroupsAllowlist.md) |
| POST | `/api/v4/projects/{id}/job_token_scope/groups_allowlist` | Add target group to allowlist. | [View](../operations/postApiV4ProjectsIdJobTokenScopeGroupsAllowlist.md) |
| DELETE | `/api/v4/projects/{id}/job_token_scope/groups_allowlist/{target_group_id}` | Delete target group from allowlist. | [View](../operations/deleteApiV4ProjectsIdJobTokenScopeGroupsAllowlistTargetGroupId.md) |
| DELETE | `/api/v4/projects/{id}/job_token_scope/allowlist/{target_project_id}` | Delete project from allowlist. | [View](../operations/deleteApiV4ProjectsIdJobTokenScopeAllowlistTargetProjectId.md) |
