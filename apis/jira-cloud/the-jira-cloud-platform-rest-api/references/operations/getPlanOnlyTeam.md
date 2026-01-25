# GET /rest/api/3/plans/plan/{planId}/team/planonly/{planOnlyTeamId}

**Resource:** [Teams in plan](../resources/Teams-in-plan.md)
**Get plan-only team**
**Operation ID:** `getPlanOnlyTeam`

Returns planning settings for a plan-only team.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `planId` | path | integer (int64) | Yes | The ID of the plan. |
| `planOnlyTeamId` | path | integer (int64) | Yes | The ID of the plan-only team. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |
| 404 | Returned if the plan or plan-only team is not found, or the plan-only team is not associated with the plan. |
| 409 | Returned if the plan is not active. |

**Success Response Schema:**

[GetPlanOnlyTeamResponse](../schemas/Get/GetPlanOnlyTeamResponse.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
