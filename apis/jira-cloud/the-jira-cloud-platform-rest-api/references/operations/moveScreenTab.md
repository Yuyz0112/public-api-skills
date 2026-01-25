# POST /rest/api/3/screens/{screenId}/tabs/{tabId}/move/{pos}

**Resource:** [Screen tabs](../resources/Screen-tabs.md)
**Move screen tab**
**Operation ID:** `moveScreenTab`

Moves a screen tab.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |
| `tabId` | path | integer (int64) | Yes | The ID of the screen tab. |
| `pos` | path | integer (int32) | Yes | The position of tab. The base index is 0. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen or screen tab is not found or the position is invalid. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
