# POST /api/v4/import/github/cancel

**Resource:** [Project import](../resources/Project-import.md)
**Cancel GitHub project import**
**Operation ID:** `postApiV4ImportGithubCancel`

This feature was introduced in GitLab 15.5

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
| 503 | Service unavailable |

**Success Response Schema:**

[ProjectImportEntity](../schemas/Project/ProjectImportEntity.md)

