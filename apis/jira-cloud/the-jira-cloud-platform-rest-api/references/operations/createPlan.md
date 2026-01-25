# POST /rest/api/3/plans/plan

**Resource:** [Plans](../resources/Plans.md)
**Create plan**
**Operation ID:** `createPlan`

Creates a plan.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `useGroupId` | query | boolean | No | Whether to accept group IDs instead of group names. Group names are deprecated. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreatePlanRequest](../schemas/Create/CreatePlanRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
