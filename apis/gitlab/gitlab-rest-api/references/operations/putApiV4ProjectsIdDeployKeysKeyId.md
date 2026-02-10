# PUT /api/v4/projects/{id}/deploy_keys/{key_id}

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Update deploy key**
**Operation ID:** `putApiV4ProjectsIdDeployKeysKeyId`

Updates a deploy key for a project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `key_id` | path | integer | Yes | The ID of the deploy key |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeployKey](../schemas/APIEntitiesDeployKey/APIEntitiesDeployKey.md)

