# GET /api/v4/projects/{id}/job_token_scope/groups_allowlist

**Resource:** [Projects job token scope](../resources/Projects-job-token-scope.md)
**Fetch project groups allowlist for CI_JOB_TOKEN access settings.**
**Operation ID:** `getApiV4ProjectsIdJobTokenScopeGroupsAllowlist`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesBasicProjectDetails](../schemas/APIEntitiesBasicProjectDetails/APIEntitiesBasicProjectDetails.md)

