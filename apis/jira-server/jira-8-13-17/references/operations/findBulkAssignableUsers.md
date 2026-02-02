# GET /user/assignable/multiProjectSearch

**Resource:** [user](../resources/user.md)
**Operation ID:** `findBulkAssignableUsers`

Returns a list of users that match the search string and can be assigned issues for all the given projects.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | the username |
| `projectKeys` | query | string | No | the keys of the projects we are finding assignable users for, comma-separated |
| `startAt` | query | integer (int32) | No | the index of the first user to return (0-based) |
| `maxResults` | query | integer (int32) | No | the maximum number of users to return (defaults to 50). The maximum allowed value is 1000.
                       If you specify a value that is higher than this number, your search results will be truncated. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

