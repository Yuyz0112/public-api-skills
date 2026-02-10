# POST /api/v4/projects/{id}/environments

**Resource:** [Environments](../resources/Environments.md)
**Create a new environment**
**Operation ID:** `postApiV4ProjectsIdEnvironments`

Creates a new environment with the given name and `external_url`. It returns `201` if the environment was successfully created, `400` for wrong parameters. This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Request Body

**Required:** Yes

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

