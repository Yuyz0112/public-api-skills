# PUT /rest/api/3/notificationscheme/{id}/notification

**Resource:** [Issue notification schemes](../resources/Issue-notification-schemes.md)
**Add notifications to notification scheme**
**Operation ID:** `addNotifications`

Adds notifications to a notification scheme. You can add up to 1000 notifications per request.

*Deprecated: The notification type `EmailAddress` is no longer supported in Cloud. Refer to the [changelog](https://developer.atlassian.com/cloud/jira/platform/changelog/#CHANGE-1031) for more details.*

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the notification scheme. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddNotificationsDetails](../schemas/Add/AddNotificationsDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the notification scheme isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
