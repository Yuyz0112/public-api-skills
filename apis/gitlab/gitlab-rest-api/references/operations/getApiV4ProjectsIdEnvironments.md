# GET /api/v4/projects/{id}/environments

**Resource:** [Environments](../resources/Environments.md)
**List environments**
**Operation ID:** `getApiV4ProjectsIdEnvironments`

Get all environments for a given project. This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `name` | query | string | No | Return the environment with this name. Mutually exclusive with search |
| `search` | query | string | No | Return list of environments matching the search criteria. Mutually exclusive with name. Must be at least 3 characters. |
| `states` | query | enum: stopped, stopping, available | No | List all environments that match a specific state. Accepted values: `available`, `stopping`, or `stopped`. If no state value given, returns all environments |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEnvironment](../schemas/APIEntitiesEnvironment/APIEntitiesEnvironment.md)

