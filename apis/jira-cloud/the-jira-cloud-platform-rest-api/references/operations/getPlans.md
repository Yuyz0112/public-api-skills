# GET /rest/api/3/plans/plan

**Resource:** [Plans](../resources/Plans.md)
**Get plans paginated**
**Operation ID:** `getPlans`

Returns a [paginated](#pagination) list of plans.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `includeTrashed` | query | boolean | No | Whether to include trashed plans in the results. |
| `includeArchived` | query | boolean | No | Whether to include archived plans in the results. |
| `cursor` | query | string | No | The cursor to start from. If not provided, the first page will be returned. |
| `maxResults` | query | integer (int32) | No | The maximum number of plans to return per page. The maximum value is 50. The default value is 50. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the user is not logged in. |
| 403 | Returned if the site has no premium edition of Jira or if the user does not have the Administer Jira global permission. |

**Success Response Schema:**

[PageWithCursorGetPlanResponseForPage](../schemas/Page/PageWithCursorGetPlanResponseForPage.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
