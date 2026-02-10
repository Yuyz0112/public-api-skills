# DELETE /api/v4/projects/{id}/environments/{environment_id}

**Resource:** [Environments](../resources/Environments.md)
**Delete an environment**
**Operation ID:** `deleteApiV4ProjectsIdEnvironmentsEnvironmentId`

It returns 204 if the environment was successfully deleted, and 404 if the environment does not exist. This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `environment_id` | path | integer | Yes | The ID of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 404 | Not found |

