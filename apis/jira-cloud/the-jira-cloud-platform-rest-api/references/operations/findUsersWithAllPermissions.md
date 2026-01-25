# GET /rest/api/3/user/permission/search

**Resource:** [User search](../resources/User-search.md)
**Find users with permissions**
**Operation ID:** `findUsersWithAllPermissions`

Returns a list of users who fulfill these criteria:

 *  their user attributes match a search string.
 *  they have a set of permissions for a project or issue.

If no search string is provided, a list of all users with the permissions is returned.

This operation takes the users in the range defined by `startAt` and `maxResults`, up to the thousandth user, and then returns only the users from that range that match the search string and have permission for the project or issue. This means the operation usually returns fewer users than specified in `maxResults`. To get all the users who match the search string and have permission for the project or issue, use [Get all users](#api-rest-api-3-users-search-get) and filter the records in your code.

Privacy controls are applied to the response based on the users' preferences. This could mean, for example, that the user's email address is hidden. See the [Profile visibility overview](https://developer.atlassian.com/cloud/jira/platform/profile-visibility/) for more details.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg), to get users for any project.
 *  *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for a project, to get users for that project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | No | A query string that is matched against user attributes, such as `displayName` and `emailAddress`, to find relevant users. The string can match the prefix of the attribute's value. For example, *query=john* matches a user with a `displayName` of *John Smith* and a user with an `emailAddress` of *johnson@example.com*. Required, unless `accountId` is specified. |
| `username` | query | string | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `accountId` | query | string | No | A query string that is matched exactly against user `accountId`. Required, unless `query` is specified. |
| `permissions` | query | string | Yes | A comma separated list of permissions. Permissions can be specified as any:

 *  permission returned by [Get all permissions](#api-rest-api-3-permissions-get).
 *  custom project permission added by Connect apps.
 *  (deprecated) one of the following:
    
     *  ASSIGNABLE\_USER
     *  ASSIGN\_ISSUE
     *  ATTACHMENT\_DELETE\_ALL
     *  ATTACHMENT\_DELETE\_OWN
     *  BROWSE
     *  CLOSE\_ISSUE
     *  COMMENT\_DELETE\_ALL
     *  COMMENT\_DELETE\_OWN
     *  COMMENT\_EDIT\_ALL
     *  COMMENT\_EDIT\_OWN
     *  COMMENT\_ISSUE
     *  CREATE\_ATTACHMENT
     *  CREATE\_ISSUE
     *  DELETE\_ISSUE
     *  EDIT\_ISSUE
     *  LINK\_ISSUE
     *  MANAGE\_WATCHER\_LIST
     *  MODIFY\_REPORTER
     *  MOVE\_ISSUE
     *  PROJECT\_ADMIN
     *  RESOLVE\_ISSUE
     *  SCHEDULE\_ISSUE
     *  SET\_ISSUE\_SECURITY
     *  TRANSITION\_ISSUE
     *  VIEW\_VERSION\_CONTROL
     *  VIEW\_VOTERS\_AND\_WATCHERS
     *  VIEW\_WORKFLOW\_READONLY
     *  WORKLOG\_DELETE\_ALL
     *  WORKLOG\_DELETE\_OWN
     *  WORKLOG\_EDIT\_ALL
     *  WORKLOG\_EDIT\_OWN
     *  WORK\_ISSUE |
| `issueKey` | query | string | No | The issue key for the issue. |
| `projectKey` | query | string | No | The project key for the project (case sensitive). |
| `startAt` | query | integer (int32) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  `issueKey` or `projectKey` is missing.
 *  `query` or `accountId` is missing.
 *  `query` and `accountId` are provided.
 *  `permissions` is empty or contains an invalid entry. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the issue or project is not found. |
| 429 | Returned if the rate limit is exceeded. User search endpoints share a collective rate limit for the tenant, in addition to Jira's normal rate limiting you may receive a rate limit for user search. Please respect the Retry-After header. |

**Success Response Schema:**

Array of [User](../schemas/User/User.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
