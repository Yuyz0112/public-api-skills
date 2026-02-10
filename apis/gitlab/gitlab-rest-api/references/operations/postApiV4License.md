# POST /api/v4/license

**Resource:** [Licenses](../resources/Licenses.md)
**Add a new license**
**Operation ID:** `postApiV4License`

Adds a new licence

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |

**Success Response Schema:**

[APIEntitiesGitlabLicenseWithActiveUsers](../schemas/APIEntitiesGitlabLicenseWithActiveUsers/APIEntitiesGitlabLicenseWithActiveUsers.md)

