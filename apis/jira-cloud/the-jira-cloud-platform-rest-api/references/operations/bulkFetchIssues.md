# POST /rest/api/3/issue/bulkfetch

**Resource:** [Issues](../resources/Issues.md)
**Bulk fetch issues**
**Operation ID:** `bulkFetchIssues`

Returns the details for a set of requested issues. You can request up to 100 issues.

Each issue is identified by its ID or key, however, if the identifier doesn't match an issue, a case-insensitive search and check for moved issues is performed. If a matching issue is found its details are returned, a 302 or other redirect is **not** returned.

Issues will be returned in ascending `id` order. If there are errors, Jira will return a list of issues which couldn't be fetched along with error messages.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Issues are included in the response where the user has:

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Request Body

A JSON object containing the information about which issues and fields to fetch.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BulkFetchIssueRequestBean](../schemas/Bulk/BulkFetchIssueRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. A response may contain both successful issues and issue errors. |
| 400 | Returned if no issue IDs/keys were present, or more than 100 issue IDs/keys were requested. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[BulkIssueResults](../schemas/Bulk/BulkIssueResults.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
