# POST /rest/api/3/search/approximate-count

**Resource:** [Issue search](../resources/Issue-search.md)
**Count issues using JQL**
**Operation ID:** `countIssues`

Provide an estimated count of the issues that match the [JQL](https://confluence.atlassian.com/x/egORLQ). Recent updates might not be immediately visible in the returned output. This endpoint requires JQL to be bounded.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Issues are included in the response where the user has:

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the issue.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Request Body

A JSON object containing the search request.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [JQLCountRequestBean](../schemas/JQLCountRequestBean/JQLCountRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the JQL query cannot be parsed. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[JQLCountResultsBean](../schemas/JQLCountResultsBean/JQLCountResultsBean.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
