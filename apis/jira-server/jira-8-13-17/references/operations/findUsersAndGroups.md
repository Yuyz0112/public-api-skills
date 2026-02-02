# GET /groupuserpicker

**Resource:** [groupuserpicker](../resources/groupuserpicker.md)
**Operation ID:** `findUsersAndGroups`

Returns a list of users and groups matching query with highlighting. This resource cannot be accessed
 anonymously.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | No | A string used to search username, Name or e-mail address |
| `maxResults` | query | integer (int32) | No | the maximum number of users to return (defaults to 50). The maximum allowed value is 1000. If
                    you specify a value that is higher than this number, your search results will be truncated. |
| `showAvatar` | query | boolean | No |  |
| `fieldId` | query | string | No | The custom field id, if this request comes from a custom field, such as a user picker. Optional. |
| `projectId` | query | string | No | The list of project ids to further restrict the search
                    This parameter can occur multiple times to pass in multiple project ids.
                    Comma separated value is not supported.
                    This parameter is only used when fieldId is present. |
| `issueTypeId` | query | string | No | The list of issue type ids to further restrict the search.
                    This parameter can occur multiple times to pass in multiple issue type ids.
                    Comma separated value is not supported.
                    Special values such as -1 (all standard issue types), -2 (all subtask issue types) are supported.
                    This parameter is only used when fieldId is present. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

