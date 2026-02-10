# POST /api/v4/projects/{id}/environments/{environment_id}/stop

**Resource:** [Environments](../resources/Environments.md)
**Stop an environment**
**Operation ID:** `postApiV4ProjectsIdEnvironmentsEnvironmentIdStop`

It returns 200 if the environment was successfully stopped.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `environment_id` | path | integer | Yes | The ID of the environment |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEnvironment](../schemas/APIEntitiesEnvironment/APIEntitiesEnvironment.md)

