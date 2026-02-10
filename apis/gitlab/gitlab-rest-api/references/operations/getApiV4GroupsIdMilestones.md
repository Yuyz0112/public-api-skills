# GET /api/v4/groups/{id}/milestones

**Resource:** [Milestones](../resources/Milestones.md)
**Get a list of group milestones**
**Operation ID:** `getApiV4GroupsIdMilestones`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `state` | query | enum: active, closed, all | No | Return "active", "closed", or "all" milestones |
| `iids` | query | any | No | The IIDs of the milestones |
| `title` | query | string | No | The title of the milestones |
| `search` | query | string | No | The search criteria for the title or description of the milestone |
| `include_parent_milestones` | query | boolean | No | Deprecated: see `include_ancestors` |
| `include_ancestors` | query | boolean | No | Include milestones from all parent groups |
| `updated_before` | query | string (date-time) | No | Return milestones updated before the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `updated_after` | query | string (date-time) | No | Return milestones updated after the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `include_descendants` | query | boolean | No | Include milestones from all subgroups and subprojects |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMilestone](../schemas/APIEntitiesMilestone/APIEntitiesMilestone.md)

