# GET /rest/api/3/project/{projectKeyOrId}/notificationscheme

**Resource:** [Projects](../resources/Projects.md)
**Get project notification scheme**
**Operation ID:** `getNotificationSchemeForProject`

Gets a [notification scheme](https://confluence.atlassian.com/x/8YdKLg) associated with the project.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectKeyOrId` | path | string | Yes | The project ID or project key (case sensitive). |
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
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user is not an administrator. |

**Success Response Schema:**

[NotificationScheme](../schemas/Notification/NotificationScheme.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
