# GET /rest/api/3/notificationscheme

**Resource:** [Issue notification schemes](../resources/Issue-notification-schemes.md)
**Get notification schemes paginated**
**Operation ID:** `getNotificationSchemes`

Returns a [paginated](#pagination) list of [notification schemes](https://confluence.atlassian.com/x/8YdKLg) ordered by the display name.

*Note that you should allow for events without recipients to appear in responses.*

**[Permissions](#permissions) required:** Permission to access Jira, however, the user must have permission to administer at least one project associated with a notification scheme for it to be returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `id` | query | string[] | No | The list of notification schemes IDs to be filtered by |
| `projectId` | query | string[] | No | The list of projects IDs to be filtered by |
| `onlyDefault` | query | boolean | No | When set to true, returns only the default notification scheme. If you provide project IDs not associated with the default, returns an empty page. The default value is false. |
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
| 200 | Returned if the request is successful. Only returns notification schemes that the user has permission to access. An empty list is returned if the user lacks permission to access all notification schemes. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[PageBeanNotificationScheme](../schemas/Page/PageBeanNotificationScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
