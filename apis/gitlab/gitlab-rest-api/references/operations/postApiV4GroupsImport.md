# POST /api/v4/groups/import

**Resource:** [Group import and export](../resources/Group-import-and-export.md)
**Create a new group import**
**Operation ID:** `postApiV4GroupsImport`

This feature was introduced in GitLab 12.8

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 503 | Service unavailable |

