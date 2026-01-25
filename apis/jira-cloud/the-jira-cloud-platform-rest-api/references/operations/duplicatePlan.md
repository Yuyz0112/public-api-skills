# POST /rest/api/3/plans/plan/{planId}/duplicate

**Resource:** [Plans](../resources/Plans.md)
**Duplicate plan**
**Operation ID:** `duplicatePlan`

Duplicates a plan.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `planId` | path | integer (int64) | Yes | The ID of the plan. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DuplicatePlanRequest](../schemas/Duplicate/DuplicatePlanRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |
| 404 | Returned if the plan to duplicate is not found. |
| 409 | Returned if the plan to duplicate is not active. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
