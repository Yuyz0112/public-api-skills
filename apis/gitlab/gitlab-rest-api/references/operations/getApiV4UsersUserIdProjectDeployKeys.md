# GET /api/v4/users/{user_id}/project_deploy_keys

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Get the project-level Deploy keys that a specified user can access to.**
**Operation ID:** `getApiV4UsersUserIdProjectDeployKeys`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | string | Yes | The ID or username of the user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesDeployKey](../schemas/APIEntitiesDeployKey/APIEntitiesDeployKey.md)

