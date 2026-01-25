# POST /rest/api/3/screens/{screenId}/tabs

**Resource:** [Screen tabs](../resources/Screen-tabs.md)
**Create screen tab**
**Operation ID:** `addScreenTab`

Creates a tab for a screen.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |

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
| 404 | Returned if the screen is not found. |

**Success Response Schema:**

[ScreenableTab](../schemas/Screenable/ScreenableTab.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
