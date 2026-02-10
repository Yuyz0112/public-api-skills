# GET /api/v4/projects/{id}/environments/{environment_id}

**Resource:** [Environments](../resources/Environments.md)
**Get a specific environment**
**Operation ID:** `getApiV4ProjectsIdEnvironmentsEnvironmentId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `environment_id` | path | integer | Yes | The ID of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEnvironment](../schemas/APIEntitiesEnvironment/APIEntitiesEnvironment.md)

