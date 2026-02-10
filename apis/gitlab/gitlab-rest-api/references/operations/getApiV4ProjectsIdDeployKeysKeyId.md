# GET /api/v4/projects/{id}/deploy_keys/{key_id}

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Get a single deploy key**
**Operation ID:** `getApiV4ProjectsIdDeployKeysKeyId`

Get a single key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `key_id` | path | integer | Yes | The ID of the deploy key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeployKeysProject](../schemas/APIEntitiesDeployKeysProject/APIEntitiesDeployKeysProject.md)

