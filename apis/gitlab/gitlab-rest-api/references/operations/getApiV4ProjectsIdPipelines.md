# GET /api/v4/projects/{id}/pipelines

**Resource:** [Pipelines](../resources/Pipelines.md)
**Get all Pipelines of the project**
**Operation ID:** `getApiV4ProjectsIdPipelines`

This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID or URL-encoded path |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `scope` | query | enum: running, pending, finished... | No | The scope of pipelines |
| `status` | query | enum: created, waiting_for_resource, preparing... | No | The status of pipelines |
| `ref` | query | string | No | The ref of pipelines |
| `sha` | query | string | No | The sha of pipelines |
| `yaml_errors` | query | boolean | No | Returns pipelines with invalid configurations |
| `username` | query | string | No | The username of the user who triggered pipelines |
| `updated_before` | query | string (date-time) | No | Return pipelines updated before the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `updated_after` | query | string (date-time) | No | Return pipelines updated after the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `created_before` | query | string (date-time) | No | Return pipelines created before the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `created_after` | query | string (date-time) | No | Return pipelines created after the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `order_by` | query | enum: id, status, ref... | No | Order pipelines |
| `sort` | query | enum: asc, desc | No | Sort pipelines |
| `source` | query | enum: unknown, push, web... | No | The source of pipelines |
| `name` | query | string | No | Filter pipelines by name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesCiPipelineBasic](../schemas/APIEntitiesCiPipelineBasic/APIEntitiesCiPipelineBasic.md)

