# POST /rest/api/3/group/user

**Resource:** [Groups](../resources/Groups.md)
**Add user to group**
**Operation ID:** `addUserToGroup`

Adds a user to a group.

**[Permissions](#permissions) required:** Site administration (that is, member of the *site-admin* [group](https://confluence.atlassian.com/x/24xjL)).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `groupname` | query | string | No | As a group's name can change, use of `groupId` is recommended to identify a group.  
The name of the group. This parameter cannot be used with the `groupId` parameter. |
| `groupId` | query | string | No | The ID of the group. This parameter cannot be used with the `groupName` parameter. |

## Request Body

The user to add to the group.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateUserToGroupBean](../schemas/Update/UpdateUserToGroupBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if:

 *  `groupname` is not provided.
 *  `accountId` is missing. |
| 401 | Returned if the authentication credentials are incorrect or missing from the request. |
| 403 | Returned if the calling user does not have the necessary permission. |
| 404 | Returned if the group or user are not found. |
| 429 | Returned if rate limiting is being enforced. |

**Success Response Schema:**

[Group](../schemas/Group/Group.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
