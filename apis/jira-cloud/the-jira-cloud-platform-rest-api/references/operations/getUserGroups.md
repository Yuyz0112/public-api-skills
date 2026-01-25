# GET /rest/api/3/user/groups

**Resource:** [Users](../resources/Users.md)
**Get user groups**
**Operation ID:** `getUserGroups`

Returns the groups to which a user belongs.

**[Permissions](#permissions) required:** *Browse users and groups* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `accountId` | query | string | Yes | The account ID of the user, which uniquely identifies the user across all Atlassian products. For example, *5b10ac8d82e05b22cc7d4ef5*. |
| `username` | query | string | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `key` | query | string | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the calling user does not have the *Browse users and groups* global permission. |
| 404 | Returned if the user is not found. |

**Success Response Schema:**

Array of [GroupName](../schemas/Group/GroupName.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
