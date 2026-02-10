# GET /api/v4/license/{id}

**Resource:** [Licenses](../resources/Licenses.md)
**Get a license**
**Operation ID:** `getApiV4LicenseId`

Gets a license

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | ID of the GitLab license |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesGitlabLicenseWithActiveUsers](../schemas/APIEntitiesGitlabLicenseWithActiveUsers/APIEntitiesGitlabLicenseWithActiveUsers.md)

