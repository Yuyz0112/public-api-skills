# DELETE /rest/api/3/notificationscheme/{notificationSchemeId}

**Resource:** [Issue notification schemes](../resources/Issue-notification-schemes.md)
**Delete notification scheme**
**Operation ID:** `deleteNotificationScheme`

Deletes a notification scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `notificationSchemeId` | path | string | Yes | The ID of the notification scheme. |

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
