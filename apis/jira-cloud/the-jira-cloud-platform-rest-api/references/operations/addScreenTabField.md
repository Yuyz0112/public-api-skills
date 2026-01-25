# POST /rest/api/3/screens/{screenId}/tabs/{tabId}/fields

**Resource:** [Screen tab fields](../resources/Screen-tab-fields.md)
**Add screen tab field**
**Operation ID:** `addScreenTabField`

Adds a field to a screen tab.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |
| `tabId` | path | integer (int64) | Yes | The ID of the screen tab. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddFieldBean](../schemas/Add/AddFieldBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen, screen tab, or field is not found. |

**Success Response Schema:**

[ScreenableField](../schemas/Screenable/ScreenableField.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
