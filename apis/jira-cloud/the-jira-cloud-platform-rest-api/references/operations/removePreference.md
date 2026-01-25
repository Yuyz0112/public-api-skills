# DELETE /rest/api/3/mypreferences

**Resource:** [Myself](../resources/Myself.md)
**Delete preference**
**Operation ID:** `removePreference`

Deletes a preference of the user, which restores the default value of system defined settings.

Note that these keys are deprecated:

 *  *jira.user.locale* The locale of the user. By default, not set. The user takes the instance locale.
 *  *jira.user.timezone* The time zone of the user. By default, not set. The user takes the instance timezone.

Use [ Update a user profile](https://developer.atlassian.com/cloud/admin/user-management/rest/#api-users-account-id-manage-profile-patch) from the user management REST API to manage timezone and locale instead.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | Yes | The key of the preference. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the key is not provided or not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
