# GET /rest/api/3/group/member

**Resource:** [Groups](../resources/Groups.md)
**Get users from group**
**Operation ID:** `getUsersFromGroup`

Returns a [paginated](#pagination) list of all users in a group.

Note that users are ordered by username, however the username is not returned in the results due to privacy reasons.

**[Permissions](#permissions) required:** either of:

 *  *Browse users and groups* [global permission](https://confluence.atlassian.com/x/x4dKLg).
 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `groupname` | query | string | No | As a group's name can change, use of `groupId` is recommended to identify a group.  
The name of the group. This parameter cannot be used with the `groupId` parameter. |
| `groupId` | query | string | No | The ID of the group. This parameter cannot be used with the `groupName` parameter. |
| `includeInactiveUsers` | query | boolean | No | Include inactive users. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page (number should be between 1 and 50). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the group name is not specified. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the calling user does not have the Administer Jira global permission. |
| 404 | Returned if the group is not found. |

**Success Response Schema:**

[PageBeanUserDetails](../schemas/Page/PageBeanUserDetails.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
