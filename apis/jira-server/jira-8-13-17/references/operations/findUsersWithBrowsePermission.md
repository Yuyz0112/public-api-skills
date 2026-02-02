# GET /user/viewissue/search

**Resource:** [user](../resources/user.md)
**Operation ID:** `findUsersWithBrowsePermission`

Returns a list of active users that match the search string. This resource cannot be accessed anonymously
 and requires the Browse Users global permission.
 Given an issue key this resource will provide a list of users that match the search string and have
 the browse issue permission for the issue provided.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | the username filter, no users returned if left blank |
| `issueKey` | query | string | No | the issue key for the issue being edited we need to find viewable users for. |
| `projectKey` | query | string | No | the optional project key to search for users with if no issueKey is supplied. |
| `startAt` | query | integer (int32) | No | the index of the first user to return (0-based) |
| `maxResults` | query | integer (int32) | No | the maximum number of users to return (defaults to 50). The maximum allowed value is 1000.
                   If you specify a value that is higher than this number, your search results will be truncated. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

