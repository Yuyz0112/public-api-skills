# POST /api/v4/import/bitbucket

**Resource:** [Project import](../resources/Project-import.md)
**Import a BitBucket Cloud repository**
**Operation ID:** `postApiV4ImportBitbucket`

This feature was introduced in GitLab 17.0.

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

[ProjectImportEntity](../schemas/Project/ProjectImportEntity.md)

