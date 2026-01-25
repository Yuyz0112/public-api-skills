# DELETE /rest/api/3/screens/{screenId}/tabs/{tabId}/fields/{id}

**Resource:** [Screen tab fields](../resources/Screen-tab-fields.md)
**Remove screen tab field**
**Operation ID:** `removeScreenTabField`

Removes a field from a screen tab.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |
| `tabId` | path | integer (int64) | Yes | The ID of the screen tab. |
| `id` | path | string | Yes | The ID of the field. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen, screen tab, or field is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
