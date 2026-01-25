# GET /rest/api/3/screens/{screenId}/tabs/{tabId}/fields

**Resource:** [Screen tab fields](../resources/Screen-tab-fields.md)
**Get all screen tab fields**
**Operation ID:** `getAllScreenTabFields`

Returns all fields for a screen tab.

**[Permissions](#permissions) required:**

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).
 *  *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) when the project key is specified, providing that the screen is associated with the project through a Screen Scheme and Issue Type Screen Scheme.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |
| `tabId` | path | integer (int64) | Yes | The ID of the screen tab. |
| `projectKey` | query | string | No | The key of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen or screen tab is not found. |

**Success Response Schema:**

Array of [ScreenableField](../schemas/Screenable/ScreenableField.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
