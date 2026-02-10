# POST /api/v4/groups/{id}/milestones

**Resource:** [Milestones](../resources/Milestones.md)
**Create a new group milestone**
**Operation ID:** `postApiV4GroupsIdMilestones`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMilestone](../schemas/APIEntitiesMilestone/APIEntitiesMilestone.md)

