# GET /api/v4/groups/{id}/milestones/{milestone_id}/issues

**Resource:** [Milestones](../resources/Milestones.md)
**Get all issues for a single group milestone**
**Operation ID:** `getApiV4GroupsIdMilestonesMilestoneIdIssues`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `milestone_id` | path | integer | Yes | The ID of a group milestone |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIssueBasic](../schemas/APIEntitiesIssueBasic/APIEntitiesIssueBasic.md)

