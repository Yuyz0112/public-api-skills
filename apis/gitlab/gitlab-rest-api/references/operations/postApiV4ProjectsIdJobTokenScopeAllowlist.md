# POST /api/v4/projects/{id}/job_token_scope/allowlist

**Resource:** [Projects job token scope](../resources/Projects-job-token-scope.md)
**Add target project to allowlist.**
**Operation ID:** `postApiV4ProjectsIdJobTokenScopeAllowlist`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | ID of user project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesBasicProjectDetails](../schemas/APIEntitiesBasicProjectDetails/APIEntitiesBasicProjectDetails.md)

