# GET /rest/api/3/groups/picker

**Resource:** [Groups](../resources/Groups.md)
**Find groups**
**Operation ID:** `findGroups`

Returns a list of groups whose names contain a query string. A list of group names can be provided to exclude groups from the results.

The primary use case for this resource is to populate a group picker suggestions list. To this end, the returned object includes the `html` field where the matched query term is highlighted in the group name with the HTML strong tag. Also, the groups list is wrapped in a response object that contains a header for use in the picker, specifically *Showing X of Y matching groups*.

The list returns with the groups sorted. If no groups match the list criteria, an empty list is returned.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg). Anonymous calls and calls by users without the required permission return an empty list.

*Browse users and groups* [global permission](https://confluence.atlassian.com/x/x4dKLg). Without this permission, calls where query is not an exact match to an existing group will return an empty list.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `accountId` | query | string | No | This parameter is deprecated, setting it does not affect the results. To find groups containing a particular user, use [Get user groups](#api-rest-api-3-user-groups-get). |
| `query` | query | string | No | The string to find in group names. |
| `exclude` | query | string[] | No | As a group's name can change, use of `excludeGroupIds` is recommended to identify a group.  
A group to exclude from the result. To exclude multiple groups, provide an ampersand-separated list. For example, `exclude=group1&exclude=group2`. This parameter cannot be used with the `excludeGroupIds` parameter. |
| `excludeId` | query | string[] | No | A group ID to exclude from the result. To exclude multiple groups, provide an ampersand-separated list. For example, `excludeId=group1-id&excludeId=group2-id`. This parameter cannot be used with the `excludeGroups` parameter. |
| `maxResults` | query | integer (int32) | No | The maximum number of groups to return. The maximum number of groups that can be returned is limited by the system property `jira.ajax.autocomplete.limit`. |
| `caseInsensitive` | query | boolean | No | Whether the search for groups should be case insensitive. |
| `userName` | query | string | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |

**Success Response Schema:**

[FoundGroups](../schemas/Found/FoundGroups.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
