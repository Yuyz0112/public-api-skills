# POST /rest/api/3/search/jql

**Resource:** [Issue search](../resources/Issue-search.md)
**Search for issues using JQL enhanced search (POST)**
**Operation ID:** `searchAndReconsileIssuesUsingJqlPost`

Searches for issues using [JQL](https://confluence.atlassian.com/x/egORLQ). Recent updates might not be immediately visible in the returned search results. If you need [read-after-write](https://developer.atlassian.com/cloud/jira/platform/search-and-reconcile/) consistency, you can utilize the `reconcileIssues` parameter to ensure stronger consistency assurances. This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Issues are included in the response where the user has:

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the issue.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SearchAndReconcileRequestBean](../schemas/Search/SearchAndReconcileRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the search request is invalid |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[SearchAndReconcileResults](../schemas/Search/SearchAndReconcileResults.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
