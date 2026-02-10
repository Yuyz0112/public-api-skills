# DELETE /api/v4/projects/{id}/deploy_keys/{key_id}

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Delete deploy key**
**Operation ID:** `deleteApiV4ProjectsIdDeployKeysKeyId`

Removes a deploy key from the project. If the deploy key is used only for this project, it's deleted from the system.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `key_id` | path | integer | Yes | The ID of the deploy key |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 404 | Not found |

