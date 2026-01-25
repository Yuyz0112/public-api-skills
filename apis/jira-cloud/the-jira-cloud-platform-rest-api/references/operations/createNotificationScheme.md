# POST /rest/api/3/notificationscheme

**Resource:** [Issue notification schemes](../resources/Issue-notification-schemes.md)
**Create notification scheme**
**Operation ID:** `createNotificationScheme`

Creates a notification scheme with notifications. You can create up to 1000 notifications per request.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateNotificationSchemeDetails](../schemas/Create/CreateNotificationSchemeDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |

**Success Response Schema:**

[NotificationSchemeId](../schemas/Notification/NotificationSchemeId.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
