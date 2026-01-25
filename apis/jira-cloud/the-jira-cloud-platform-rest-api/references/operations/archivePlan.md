# PUT /rest/api/3/plans/plan/{planId}/archive

**Resource:** [Plans](../resources/Plans.md)
**Archive plan**
**Operation ID:** `archivePlan`

Archives a plan.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `planId` | path | integer (int64) | Yes | The ID of the plan. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |
| 404 | Returned if the plan is not found. |
| 409 | Returned if the plan is not active. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
