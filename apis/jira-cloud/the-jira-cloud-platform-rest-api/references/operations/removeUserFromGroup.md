# DELETE /rest/api/3/group/user

**Resource:** [Groups](../resources/Groups.md)
**Remove user from group**
**Operation ID:** `removeUserFromGroup`

Removes a user from a group.

**[Permissions](#permissions) required:** Site administration (that is, member of the *site-admin* [group](https://confluence.atlassian.com/x/24xjL)).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `groupname` | query | string | No | As a group's name can change, use of `groupId` is recommended to identify a group.  
The name of the group. This parameter cannot be used with the `groupId` parameter. |
| `groupId` | query | string | No | The ID of the group. This parameter cannot be used with the `groupName` parameter. |
| `username` | query | string | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `accountId` | query | string | Yes | The account ID of the user, which uniquely identifies the user across all Atlassian products. For example, *5b10ac8d82e05b22cc7d4ef5*. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  `groupName` is missing.
 *  `accountId` is missing. |
| 401 | Returned if the authentication credentials are incorrect or missing from the request. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the group or user are not found. |
| 429 | Returned if rate limiting is being enforced. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
