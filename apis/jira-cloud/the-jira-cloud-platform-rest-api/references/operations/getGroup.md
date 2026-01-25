# GET /rest/api/3/group

**Resource:** [Groups](../resources/Groups.md)
**Get group**
**Operation ID:** `getGroup`
⚠️ **Deprecated**

This operation is deprecated, use [`group/member`](#api-rest-api-3-group-member-get).

Returns all users in a group.

**[Permissions](#permissions) required:** either of:

 *  *Browse users and groups* [global permission](https://confluence.atlassian.com/x/x4dKLg).
 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `groupname` | query | string | No | As a group's name can change, use of `groupId` is recommended to identify a group.  
The name of the group. This parameter cannot be used with the `groupId` parameter. |
| `groupId` | query | string | No | The ID of the group. This parameter cannot be used with the `groupName` parameter. |
| `expand` | query | string | No | List of fields to expand. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the group name is not specified. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the calling user does not have the Administer Jira global permission. |
| 404 | Returned if the group is not found. |

**Success Response Schema:**

[Group](../schemas/Group/Group.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
