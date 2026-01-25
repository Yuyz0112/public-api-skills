# DELETE /rest/api/3/plans/plan/{planId}/team/atlassian/{atlassianTeamId}

**Resource:** [Teams in plan](../resources/Teams-in-plan.md)
**Remove Atlassian team from plan**
**Operation ID:** `removeAtlassianTeam`

Removes an Atlassian team from a plan and deletes their planning settings.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `planId` | path | integer (int64) | Yes | The ID of the plan. |
| `atlassianTeamId` | path | string | Yes | The ID of the Atlassian team. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |
| 404 | Returned if the plan or Atlassian team is not found, or the Atlassian team is not associated with the plan. |
| 409 | Returned if the plan is not active. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
