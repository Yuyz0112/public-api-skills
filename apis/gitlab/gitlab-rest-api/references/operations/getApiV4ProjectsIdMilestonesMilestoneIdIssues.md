# GET /api/v4/projects/{id}/milestones/{milestone_id}/issues

**Resource:** [Milestones](../resources/Milestones.md)
**Get all issues for a single project milestone**
**Operation ID:** `getApiV4ProjectsIdMilestonesMilestoneIdIssues`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `milestone_id` | path | integer | Yes | The ID of a project milestone |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIssueBasic](../schemas/APIEntitiesIssueBasic/APIEntitiesIssueBasic.md)

