# GET /rest/api/3/groupuserpicker

**Resource:** [Group and user picker](../resources/Group-and-user-picker.md)
**Find users and groups**
**Operation ID:** `findUsersAndGroups`

Returns a list of users and groups matching a string. The string is used:

 *  for users, to find a case-insensitive match with display name and e-mail address. Note that if a user has hidden their email address in their user profile, partial matches of the email address will not find the user. An exact match is required.
 *  for groups, to find a case-sensitive match with group name.

For example, if the string *tin* is used, records with the display name *Tina*, email address *sarah@tinplatetraining.com*, and the group *accounting* would be returned.

Optionally, the search can be refined to:

 *  the projects and issue types associated with a custom field, such as a user picker. The search can then be further refined to return only users and groups that have permission to view specific:
    
     *  projects.
     *  issue types.
    
    If multiple projects or issue types are specified, they must be a subset of those enabled for the custom field or no results are returned. For example, if a field is enabled for projects A, B, and C then the search could be limited to projects B and C. However, if the search is limited to projects B and D, nothing is returned.
 *  not return Connect app users and groups.
 *  return groups that have a case-insensitive match with the query.

The primary use case for this resource is to populate a picker field suggestion list with users or groups. To this end, the returned object includes an `html` field for each list. This field highlights the matched query term in the item name with the HTML strong tag. Also, each list is wrapped in a response object that contains a header for use in a picker, specifically *Showing X of Y matching groups*.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse users and groups* [global permission](https://confluence.atlassian.com/x/yodKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | Yes | The search string. |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return in each list. |
| `showAvatar` | query | boolean | No | Whether the user avatar should be returned. If an invalid value is provided, the default value is used. |
| `fieldId` | query | string | No | The custom field ID of the field this request is for. |
| `projectId` | query | string[] | No | The ID of a project that returned users and groups must have permission to view. To include multiple projects, provide an ampersand-separated list. For example, `projectId=10000&projectId=10001`. This parameter is only used when `fieldId` is present. |
| `issueTypeId` | query | string[] | No | The ID of an issue type that returned users and groups must have permission to view. To include multiple issue types, provide an ampersand-separated list. For example, `issueTypeId=10000&issueTypeId=10001`. Special values, such as `-1` (all standard issue types) and `-2` (all subtask issue types), are supported. This parameter is only used when `fieldId` is present. |
| `avatarSize` | query | enum: xsmall, xsmall@2x, xsmall@3x... | No | The size of the avatar to return. If an invalid value is provided, the default value is used. |
| `caseInsensitive` | query | boolean | No | Whether the search for groups should be case insensitive. |
| `excludeConnectAddons` | query | boolean | No | Whether Connect app users and groups should be excluded from the search results. If an invalid value is provided, the default value is used. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the query parameter is not provided. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 429 | Returned if the rate limit is exceeded. User search endpoints share a collective rate limit for the tenant, in addition to Jira's normal rate limiting you may receive a rate limit for user search. Please respect the Retry-After header. |

**Success Response Schema:**

[FoundUsersAndGroups](../schemas/Found/FoundUsersAndGroups.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
