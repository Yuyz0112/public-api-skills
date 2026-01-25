# POST /rest/api/3/search

**Resource:** [Issue search](../resources/Issue-search.md)
**Currently being removed. Search for issues using JQL (POST)**
**Operation ID:** `searchForIssuesUsingJqlPost`
⚠️ **Deprecated**

Endpoint is currently being removed. [More details](https://developer.atlassian.com/changelog/#CHANGE-2046)

Searches for issues using [JQL](https://confluence.atlassian.com/x/egORLQ).

There is a [GET](#api-rest-api-3-search-get) version of this resource that can be used for smaller JQL query expressions.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Issues are included in the response where the user has:

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the issue.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Request Body

A JSON object containing the search request.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SearchRequestBean](../schemas/Search/SearchRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the JQL query is invalid. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[SearchResults](../schemas/Search/SearchResults.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
