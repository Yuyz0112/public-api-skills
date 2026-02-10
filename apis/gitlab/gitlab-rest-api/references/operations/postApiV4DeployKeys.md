# POST /api/v4/deploy_keys

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Create a deploy key**
**Operation ID:** `postApiV4DeployKeys`

Create a deploy key for the GitLab instance. This endpoint requires administrator access.

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

**Success Response Schema:**

[APIEntitiesDeployKey](../schemas/APIEntitiesDeployKey/APIEntitiesDeployKey.md)

