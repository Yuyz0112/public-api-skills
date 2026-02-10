# GET /api/v4/projects/{id}/milestones/{milestone_id}

**Resource:** [Milestones](../resources/Milestones.md)
**Get a single project milestone**
**Operation ID:** `getApiV4ProjectsIdMilestonesMilestoneId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `milestone_id` | path | integer | Yes | The ID of a project milestone |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMilestone](../schemas/APIEntitiesMilestone/APIEntitiesMilestone.md)

