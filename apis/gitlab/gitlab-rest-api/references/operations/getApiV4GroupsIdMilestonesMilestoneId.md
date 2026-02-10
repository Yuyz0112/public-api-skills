# GET /api/v4/groups/{id}/milestones/{milestone_id}

**Resource:** [Milestones](../resources/Milestones.md)
**Get a single group milestone**
**Operation ID:** `getApiV4GroupsIdMilestonesMilestoneId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `milestone_id` | path | integer | Yes | The ID of a group milestone |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMilestone](../schemas/APIEntitiesMilestone/APIEntitiesMilestone.md)

