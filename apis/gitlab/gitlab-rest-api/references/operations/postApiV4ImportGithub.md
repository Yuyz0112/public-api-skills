# POST /api/v4/import/github

**Resource:** [Project import](../resources/Project-import.md)
**Import a GitHub project**
**Operation ID:** `postApiV4ImportGithub`

This feature was introduced in GitLab 11.3.4.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 422 | Unprocessable entity |
| 503 | Service unavailable |

**Success Response Schema:**

[ProjectEntity](../schemas/Project/ProjectEntity.md)

