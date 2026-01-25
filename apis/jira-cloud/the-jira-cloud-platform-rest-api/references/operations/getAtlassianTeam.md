# GET /rest/api/3/plans/plan/{planId}/team/atlassian/{atlassianTeamId}

**Resource:** [Teams in plan](../resources/Teams-in-plan.md)
**Get Atlassian team in plan**
**Operation ID:** `getAtlassianTeam`

Returns planning settings for an Atlassian team in a plan.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `planId` | path | integer (int64) | Yes | The ID of the plan. |
| `atlassianTeamId` | path | string | Yes | The ID of the Atlassian team. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |
| 404 | Returned if the plan or Atlassian team is not found, or the Atlassian team is not associated with the plan. |
| 409 | Returned if the plan is not active. |

**Success Response Schema:**

[GetAtlassianTeamResponse](../schemas/Get/GetAtlassianTeamResponse.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
