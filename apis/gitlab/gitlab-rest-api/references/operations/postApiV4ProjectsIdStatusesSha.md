# POST /api/v4/projects/{id}/statuses/{sha}

**Resource:** [Commit statuses](../resources/Commit-statuses.md)
**Post status to a commit**
**Operation ID:** `postApiV4ProjectsIdStatusesSha`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the project. |
| `sha` | path | string | Yes | The commit hash |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 409 | Another update to this commit status is in progress |

**Success Response Schema:**

[APIEntitiesCommitStatus](../schemas/APIEntitiesCommitStatus/APIEntitiesCommitStatus.md)

