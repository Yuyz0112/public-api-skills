# GET /api/v4/projects/{id}/deployments

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**List project deployments**
**Operation ID:** `getApiV4ProjectsIdDeployments`

Get a list of deployments in a project. This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `order_by` | query | enum: id, iid, created_at... | No | Return deployments ordered by either one of `id`, `iid`, `created_at`, `updated_at` or `ref` fields. Default is `id` |
| `sort` | query | enum: asc, desc | No | Return deployments sorted in `asc` or `desc` order. Default is `asc` |
| `updated_after` | query | string (date-time) | No | Return deployments updated after the specified date. Expected in ISO 8601 format (`2019-03-15T08:00:00Z`) |
| `updated_before` | query | string (date-time) | No | Return deployments updated before the specified date. Expected in ISO 8601 format (`2019-03-15T08:00:00Z`) |
| `finished_after` | query | string (date-time) | No | Return deployments finished after the specified date. Expected in ISO 8601 format (`2019-03-15T08:00:00Z`) |
| `finished_before` | query | string (date-time) | No | Return deployments finished before the specified date. Expected in ISO 8601 format (`2019-03-15T08:00:00Z`) |
| `environment` | query | string | No | The name of the environment to filter deployments by |
| `status` | query | enum: created, running, success... | No | The status to filter deployments by. One of `created`, `running`, `success`, `failed`, `canceled`, or `blocked` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDeployment](../schemas/APIEntitiesDeployment/APIEntitiesDeployment.md)

