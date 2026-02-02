# GET /user/picker

**Resource:** [user](../resources/user.md)
**Operation ID:** `findUsersForPicker`

Returns a list of users matching query with highlighting.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | No | A string used to search username, Name or e-mail address |
| `maxResults` | query | integer (int32) | No | the maximum number of users to return (defaults to 50). The maximum allowed value is 1000.
                   If you specify a value that is higher than this number, your search results will be truncated. |
| `showAvatar` | query | boolean | No |  |
| `exclude` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

