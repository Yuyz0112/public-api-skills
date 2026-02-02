# GET /user/assignable/search

**Resource:** [user](../resources/user.md)
**Operation ID:** `findAssignableUsers`

Returns a list of users that match the search string. This resource cannot be accessed anonymously.
 Please note that this resource should be called with an issue key when a list of assignable users is retrieved
 for editing.  For create only a project key should be supplied.  The list of assignable users may be incorrect
 if it's called with the project key for editing.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | the username |
| `project` | query | string | No | the key of the project we are finding assignable users for |
| `issueKey` | query | string | No | the issue key for the issue being edited we need to find assignable users for. |
| `startAt` | query | integer (int32) | No | the index of the first user to return (0-based) |
| `maxResults` | query | integer (int32) | No | the maximum number of users to return (defaults to 50). The maximum allowed value is 1000.
                   If you specify a value that is higher than this number, your search results will be truncated. |
| `actionDescriptorId` | query | integer (int32) | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

