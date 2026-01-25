# GET /rest/api/3/issue/{issueIdOrKey}/changelog

**Resource:** [Issues](../resources/Issues.md)
**Get changelogs**
**Operation ID:** `getChangeLogs`

Returns a [paginated](#pagination) list of all changelogs for an issue sorted by date, starting from the oldest.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `startAt` | query | integer (int32) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 404 | Returned if the issue is not found or the user does not have permission to view it. |

**Success Response Schema:**

[PageBeanChangelog](../schemas/Page/PageBeanChangelog.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
