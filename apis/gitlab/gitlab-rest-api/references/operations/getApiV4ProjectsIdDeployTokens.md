# GET /api/v4/projects/{id}/deploy_tokens

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**List project deploy tokens**
**Operation ID:** `getApiV4ProjectsIdDeployTokens`

Get a list of a project's deploy tokens. This feature was introduced in GitLab 12.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `active` | query | boolean | No | Limit by active status |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeployToken](../schemas/APIEntitiesDeployToken/APIEntitiesDeployToken.md)

