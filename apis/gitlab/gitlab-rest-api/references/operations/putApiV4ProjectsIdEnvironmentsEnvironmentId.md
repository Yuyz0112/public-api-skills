# PUT /api/v4/projects/{id}/environments/{environment_id}

**Resource:** [Environments](../resources/Environments.md)
**Update an existing environment**
**Operation ID:** `putApiV4ProjectsIdEnvironmentsEnvironmentId`

Updates an existing environment name and/or `external_url`. It returns `200` if the environment was successfully updated. In case of an error, a status code `400` is returned. This feature was introduced in GitLab 8.11.

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
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEnvironment](../schemas/APIEntitiesEnvironment/APIEntitiesEnvironment.md)

