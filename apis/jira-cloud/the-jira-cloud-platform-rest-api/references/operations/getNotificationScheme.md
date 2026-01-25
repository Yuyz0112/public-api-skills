# GET /rest/api/3/notificationscheme/{id}

**Resource:** [Issue notification schemes](../resources/Issue-notification-schemes.md)
**Get notification scheme**
**Operation ID:** `getNotificationScheme`

Returns a [notification scheme](https://confluence.atlassian.com/x/8YdKLg), including the list of events and the recipients who will receive notifications for those events.

**[Permissions](#permissions) required:** Permission to access Jira, however, the user must have permission to administer at least one project associated with the notification scheme.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the notification scheme. Use [Get notification schemes paginated](#api-rest-api-3-notificationscheme-get) to get a list of notification scheme IDs. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `all` Returns all expandable information
 *  `field` Returns information about any custom fields assigned to receive an event
 *  `group` Returns information about any groups assigned to receive an event
 *  `notificationSchemeEvents` Returns a list of event associations. This list is returned for all expandable information
 *  `projectRole` Returns information about any project roles assigned to receive an event
 *  `user` Returns information about any users assigned to receive an event |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the notification scheme is not found or the user does not have permission to view it. |

**Success Response Schema:**

[NotificationScheme](../schemas/Notification/NotificationScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
