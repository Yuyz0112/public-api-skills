# POST /api/v4/projects/{id}/deploy_keys/{key_id}/enable

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Enable a deploy key**
**Operation ID:** `postApiV4ProjectsIdDeployKeysKeyIdEnable`

Enables a deploy key for a project so this can be used. Returns the enabled key, with a status code 201 when successful. This feature was added in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `key_id` | path | integer | Yes | The ID of the deploy key |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeployKey](../schemas/APIEntitiesDeployKey/APIEntitiesDeployKey.md)

