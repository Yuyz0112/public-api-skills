# GET /api/v4/deploy_tokens

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**List all deploy tokens**
**Operation ID:** `getApiV4DeployTokens`

Get a list of all deploy tokens across the GitLab instance. This endpoint requires administrator access. This feature was introduced in GitLab 12.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `active` | query | boolean | No | Limit by active status |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesDeployToken](../schemas/APIEntitiesDeployToken/APIEntitiesDeployToken.md)

