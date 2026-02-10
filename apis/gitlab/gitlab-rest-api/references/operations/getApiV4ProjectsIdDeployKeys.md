# GET /api/v4/projects/{id}/deploy_keys

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**List deploy keys for project**
**Operation ID:** `getApiV4ProjectsIdDeployKeys`

Get a list of a project's deploy keys.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeployKeysProject](../schemas/APIEntitiesDeployKeysProject/APIEntitiesDeployKeysProject.md)

