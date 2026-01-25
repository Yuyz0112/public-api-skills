# POST /rest/api/3/screens

**Resource:** [Screens](../resources/Screens.md)
**Create screen**
**Operation ID:** `createScreen`

Creates a screen with a default field tab.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ScreenDetails](../schemas/Screen/ScreenDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |

**Success Response Schema:**

[Screen](../schemas/Screen/Screen.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
