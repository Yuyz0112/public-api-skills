# GET /api/v4/groups/{id}/milestones/{milestone_id}/merge_requests

**Resource:** [Milestones](../resources/Milestones.md)
**Get all merge requests for a single group milestone**
**Operation ID:** `getApiV4GroupsIdMilestonesMilestoneIdMergeRequests`

This feature was introduced in GitLab 9.

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

[APIEntitiesMergeRequestBasic](../schemas/APIEntitiesMergeRequestBasic/APIEntitiesMergeRequestBasic.md)

