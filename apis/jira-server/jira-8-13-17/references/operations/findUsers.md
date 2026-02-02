# GET /user/search

**Resource:** [user](../resources/user.md)
**Operation ID:** `findUsers`

Returns a list of users that match the search string. This resource cannot be accessed anonymously.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | A query string used to search username, name or e-mail address |
| `startAt` | query | integer (int32) | No | the index of the first user to return (0-based) |
| `maxResults` | query | integer (int32) | No | the maximum number of users to return (defaults to 50). The maximum allowed value is 1000.
                        If you specify a value that is higher than this number, your search results will be truncated. |
| `includeActive` | query | boolean | No | If true, then active users are included in the results (default true) |
| `includeInactive` | query | boolean | No | If true, then inactive users are included in the results (default false) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

