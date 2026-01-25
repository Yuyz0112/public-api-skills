# PUT /rest/api/3/notificationscheme/{id}

**Resource:** [Issue notification schemes](../resources/Issue-notification-schemes.md)
**Update notification scheme**
**Operation ID:** `updateNotificationScheme`

Updates a notification scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the notification scheme. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateNotificationSchemeDetails](../schemas/Update/UpdateNotificationSchemeDetails.md)

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
