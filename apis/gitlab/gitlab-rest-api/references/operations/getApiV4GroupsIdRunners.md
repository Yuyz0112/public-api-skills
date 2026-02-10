# GET /api/v4/groups/{id}/runners

**Resource:** [Runners](../resources/Runners.md)
**Get runners available for group**
**Operation ID:** `getApiV4GroupsIdRunners`

List all runners available in the group as well as its ancestor groups, including any allowed shared runners.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
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
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesCiRunner](../schemas/APIEntitiesCiRunner/APIEntitiesCiRunner.md)

