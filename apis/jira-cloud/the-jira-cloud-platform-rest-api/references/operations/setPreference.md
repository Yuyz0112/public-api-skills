# PUT /rest/api/3/mypreferences

**Resource:** [Myself](../resources/Myself.md)
**Set preference**
**Operation ID:** `setPreference`

Creates a preference for the user or updates a preference's value by sending a plain text string. For example, `false`. An arbitrary preference can be created with the value containing up to 255 characters. In addition, the following keys define system preferences that can be set or created:

 *  *user.notifications.mimetype* The mime type used in notifications sent to the user. Defaults to `html`.
 *  *user.default.share.private* Whether new [ filters](https://confluence.atlassian.com/x/eQiiLQ) are set to private. Defaults to `true`.
 *  *user.keyboard.shortcuts.disabled* Whether keyboard shortcuts are disabled. Defaults to `false`.
 *  *user.autowatch.disabled* Whether the user automatically watches issues they create or add a comment to. By default, not set: the user takes the instance autowatch setting.
 *  *user.notifiy.own.changes* Whether the user gets notified of their own changes.

Note that these keys are deprecated:

 *  *jira.user.locale* The locale of the user. By default, not set. The user takes the instance locale.
 *  *jira.user.timezone* The time zone of the user. By default, not set. The user takes the instance timezone.

These system preferences keys will be deprecated by 15/07/2024. You can still use these keys to create arbitrary preferences, but it will not have any impact on Notification behaviour.

 *  *user.notifications.watcher* Whether the user gets notified when they are watcher.
 *  *user.notifications.assignee* Whether the user gets notified when they are assignee.
 *  *user.notifications.reporter* Whether the user gets notified when they are reporter.
 *  *user.notifications.mentions* Whether the user gets notified when they are mentions.

Use [ Update a user profile](https://developer.atlassian.com/cloud/admin/user-management/rest/#api-users-account-id-manage-profile-patch) from the user management REST API to manage timezone and locale instead.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | Yes | The key of the preference. The maximum length is 255 characters. |

## Request Body

The value of the preference as a plain text string. The maximum length is 255 characters.

**Required:** Yes

**Content Types:** `application/json`, `text/plain`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the key or value is not provided or invalid. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
