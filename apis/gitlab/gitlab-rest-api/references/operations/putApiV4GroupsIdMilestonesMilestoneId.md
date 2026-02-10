# PUT /api/v4/groups/{id}/milestones/{milestone_id}

**Resource:** [Milestones](../resources/Milestones.md)
**Update an existing group milestone**
**Operation ID:** `putApiV4GroupsIdMilestonesMilestoneId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `milestone_id` | path | integer | Yes | The milestone ID number |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMilestone](../schemas/APIEntitiesMilestone/APIEntitiesMilestone.md)

