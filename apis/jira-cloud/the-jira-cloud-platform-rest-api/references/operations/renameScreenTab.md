# PUT /rest/api/3/screens/{screenId}/tabs/{tabId}

**Resource:** [Screen tabs](../resources/Screen-tabs.md)
**Update screen tab**
**Operation ID:** `renameScreenTab`

Updates the name of a screen tab.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |
| `tabId` | path | integer (int64) | Yes | The ID of the screen tab. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ScreenableTab](../schemas/Screenable/ScreenableTab.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen or screen tab is not found. |

**Success Response Schema:**

[ScreenableTab](../schemas/Screenable/ScreenableTab.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
