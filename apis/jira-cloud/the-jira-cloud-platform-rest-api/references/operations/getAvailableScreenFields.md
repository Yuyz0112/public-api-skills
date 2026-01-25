# GET /rest/api/3/screens/{screenId}/availableFields

**Resource:** [Screens](../resources/Screens.md)
**Get available screen fields**
**Operation ID:** `getAvailableScreenFields`

Returns the fields that can be added to a tab on a screen.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen is not found. |

**Success Response Schema:**

Array of [ScreenableField](../schemas/Screenable/ScreenableField.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
