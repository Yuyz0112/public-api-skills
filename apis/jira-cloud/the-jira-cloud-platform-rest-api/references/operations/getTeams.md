# GET /rest/api/3/plans/plan/{planId}/team

**Resource:** [Teams in plan](../resources/Teams-in-plan.md)
**Get teams in plan paginated**
**Operation ID:** `getTeams`

Returns a [paginated](#pagination) list of plan-only and Atlassian teams in a plan.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `planId` | path | integer (int64) | Yes | The ID of the plan. |
| `cursor` | query | string | No | The cursor to start from. If not provided, the first page will be returned. |
| `maxResults` | query | integer (int32) | No | The maximum number of plan teams to return per page. The maximum value is 50. The default value is 50. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |
| 404 | Returned if the plan is not found. |

**Success Response Schema:**

[PageWithCursorGetTeamResponseForPage](../schemas/Page/PageWithCursorGetTeamResponseForPage.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
