# GET /rest/api/3/plans/plan/{planId}

**Resource:** [Plans](../resources/Plans.md)
**Get plan**
**Operation ID:** `getPlan`

Returns a plan.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `planId` | path | integer (int64) | Yes | The ID of the plan. |
| `useGroupId` | query | boolean | No | Whether to return group IDs instead of group names. Group names are deprecated. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |
| 404 | Returned if the plan is not found. |

**Success Response Schema:**

[GetPlanResponse](../schemas/Get/GetPlanResponse.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
