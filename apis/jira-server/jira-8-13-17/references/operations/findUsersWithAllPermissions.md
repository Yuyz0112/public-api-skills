# GET /user/permission/search

**Resource:** [user](../resources/user.md)
**Operation ID:** `findUsersWithAllPermissions`

Returns a list of active users that match the search string and have all specified permissions for the project or issue.<br>
 This resource can be accessed by users with ADMINISTER_PROJECT permission for the project or global ADMIN or SYSADMIN rights.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | the username filter, list includes all users if unspecified |
| `permissions` | query | string | No | comma separated list of permissions for project or issue returned users must have, see
                    <a href="https://developer.atlassian.com/static/javadoc/jira/6.0/reference/com/atlassian/jira/security/Permissions.Permission.html">Permissions</a>
                    JavaDoc for the list of all possible permissions. |
| `issueKey` | query | string | No | the issue key for the issue for which returned users have specified permissions. |
| `projectKey` | query | string | No | the optional project key to search for users with if no issueKey is supplied. |
| `startAt` | query | integer (int32) | No | the index of the first user to return (0-based) |
| `maxResults` | query | integer (int32) | No | the maximum number of users to return (defaults to 50). The maximum allowed value is 1000.
                    If you specify a value that is higher than this number, your search results will be truncated. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

