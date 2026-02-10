# PUT /api/v4/projects/{id}/milestones/{milestone_id}

**Resource:** [Milestones](../resources/Milestones.md)
**Update an existing project milestone**
**Operation ID:** `putApiV4ProjectsIdMilestonesMilestoneId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `milestone_id` | path | integer | Yes | The milestone ID number |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMilestone](../schemas/APIEntitiesMilestone/APIEntitiesMilestone.md)

