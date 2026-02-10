# GET /api/v4/deploy_keys

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**List all deploy keys**
**Operation ID:** `getApiV4DeployKeys`

Get a list of all deploy keys across all projects of the GitLab instance. This endpoint requires administrator access and is not available on GitLab.com.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `public` | query | boolean | No | Only return deploy keys that are public |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesDeployKey](../schemas/APIEntitiesDeployKey/APIEntitiesDeployKey.md)

