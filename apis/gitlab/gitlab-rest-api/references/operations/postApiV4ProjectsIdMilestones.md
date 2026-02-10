# POST /api/v4/projects/{id}/milestones

**Resource:** [Milestones](../resources/Milestones.md)
**Create a new project milestone**
**Operation ID:** `postApiV4ProjectsIdMilestones`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMilestone](../schemas/APIEntitiesMilestone/APIEntitiesMilestone.md)

