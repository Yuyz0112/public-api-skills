# POST /rest/api/3/jql/match

**Resource:** [Issue search](../resources/Issue-search.md)
**Check issues against JQL**
**Operation ID:** `matchIssues`

Checks whether one or more issues would be returned by one or more JQL queries.

**[Permissions](#permissions) required:** None, however, issues are only matched against JQL queries where the user has:

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssuesAndJQLQueries](../schemas/Issues/IssuesAndJQLQueries.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if `jqls` exceeds the maximum number of JQL queries or `issueIds` exceeds the maximum number of issue IDs. |

**Success Response Schema:**

[IssueMatches](../schemas/Issue/IssueMatches.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
