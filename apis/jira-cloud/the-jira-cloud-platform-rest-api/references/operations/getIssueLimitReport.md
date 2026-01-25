# GET /rest/api/3/issue/limit/report

**Resource:** [Issues](../resources/Issues.md)
**Get issue limit report**
**Operation ID:** `getIssueLimitReport`

Returns all issues breaching and approaching per-issue limits.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) is required for the project the issues are in. Results may be incomplete otherwise
 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `isReturningKeys` | query | boolean | No | Return issue keys instead of issue ids in the response.

Usage: Add `?isReturningKeys=true` to the end of the path to request issue keys. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to complete this request. |

**Success Response Schema:**

[IssueLimitReportResponseBean](../schemas/Issue/IssueLimitReportResponseBean.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
