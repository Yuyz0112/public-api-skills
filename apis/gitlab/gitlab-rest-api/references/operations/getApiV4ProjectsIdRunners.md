# GET /api/v4/projects/{id}/runners

**Resource:** [Runners](../resources/Runners.md)
**Get runners available for project**
**Operation ID:** `getApiV4ProjectsIdRunners`

List all runners available in the project, including from ancestor groups and any allowed shared runners.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `scope` | query | enum: specific, shared, instance_type... | No | Deprecated: Use `type` or `status` instead. The scope of runners to return |
| `type` | query | enum: instance_type, group_type, project_type | No | The type of runners to return |
| `paused` | query | boolean | No | Whether to include only runners that are accepting or ignoring new jobs |
| `status` | query | enum: active, paused, online... | No | The status of runners to return |
| `tag_list` | query | any | No | A list of runner tags |
| `version_prefix` | query | string | No | The version prefix of runners to return |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Scope contains invalid value |
| 403 | No access granted |

**Success Response Schema:**

[APIEntitiesCiRunner](../schemas/APIEntitiesCiRunner/APIEntitiesCiRunner.md)

