# GET /rest/api/3/mypreferences

**Resource:** [Myself](../resources/Myself.md)
**Get preference**
**Operation ID:** `getPreference`

Returns the value of a preference of the current user.

Note that these keys are deprecated:

 *  *jira.user.locale* The locale of the user. By default this is not set and the user takes the locale of the instance.
 *  *jira.user.timezone* The time zone of the user. By default this is not set and the user takes the timezone of the instance.

These system preferences keys will be deprecated by 15/07/2024. You can still retrieve these keys, but it will not have any impact on Notification behaviour.

 *  *user.notifications.watcher* Whether the user gets notified when they are watcher.
 *  *user.notifications.assignee* Whether the user gets notified when they are assignee.
 *  *user.notifications.reporter* Whether the user gets notified when they are reporter.
 *  *user.notifications.mentions* Whether the user gets notified when they are mentions.

Use [ Update a user profile](https://developer.atlassian.com/cloud/admin/user-management/rest/#api-users-account-id-manage-profile-patch) from the user management REST API to manage timezone and locale instead.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | Yes | The key of the preference. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the key is not provided or not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
