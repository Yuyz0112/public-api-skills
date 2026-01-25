# GET /rest/api/3/screens/{screenId}/tabs

**Resource:** [Screen tabs](../resources/Screen-tabs.md)
**Get all screen tabs**
**Operation ID:** `getAllScreenTabs`

Returns the list of tabs for a screen.

**[Permissions](#permissions) required:**

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).
 *  *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) when the project key is specified, providing that the screen is associated with the project through a Screen Scheme and Issue Type Screen Scheme.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |
| `projectKey` | query | string | No | The key of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the screen ID is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen is not found. |

**Success Response Schema:**

Array of [ScreenableTab](../schemas/Screenable/ScreenableTab.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
