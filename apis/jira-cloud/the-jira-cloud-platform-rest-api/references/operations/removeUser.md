# DELETE /rest/api/3/user

**Resource:** [Users](../resources/Users.md)
**Delete user**
**Operation ID:** `removeUser`

Deletes a user. If the operation completes successfully then the user is removed from Jira's user base. This operation does not delete the user's Atlassian account.

**[Permissions](#permissions) required:** Site administration (that is, membership of the *site-admin* [group](https://confluence.atlassian.com/x/24xjL)).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `accountId` | query | string | Yes | The account ID of the user, which uniquely identifies the user across all Atlassian products. For example, *5b10ac8d82e05b22cc7d4ef5*. |
| `username` | query | string | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `key` | query | string | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the user cannot be removed. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the user is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
