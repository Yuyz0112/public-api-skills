# PUT /rest/api/3/plans/plan/{planId}/team/planonly/{planOnlyTeamId}

**Resource:** [Teams in plan](../resources/Teams-in-plan.md)
**Update plan-only team**
**Operation ID:** `updatePlanOnlyTeam`

Updates any of the following planning settings of a plan-only team using [JSON Patch](https://datatracker.ietf.org/doc/html/rfc6902).

 *  name
 *  planningStyle
 *  issueSourceId
 *  sprintLength
 *  capacity
 *  memberAccountIds

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

*Note that "add" operations do not respect array indexes in target locations. Call the "Get plan-only team" endpoint to find out the order of array elements.*

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `planId` | path | integer (int64) | Yes | The ID of the plan. |
| `planOnlyTeamId` | path | integer (int64) | Yes | The ID of the plan-only team. |

## Request Body

**Required:** Yes

**Content Types:** `application/json-patch+json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |
| 404 | Returned if the plan or plan-only team is not found, or the plan-only team is not associated with the plan. |
| 409 | Returned if the plan is not active. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
