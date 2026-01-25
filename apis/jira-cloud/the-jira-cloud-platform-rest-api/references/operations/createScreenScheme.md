# POST /rest/api/3/screenscheme

**Resource:** [Screen schemes](../resources/Screen-schemes.md)
**Create screen scheme**
**Operation ID:** `createScreenScheme`

Creates a screen scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ScreenSchemeDetails](../schemas/Screen/ScreenSchemeDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if a screen used as one of the screen types in the screen scheme is not found. |

**Success Response Schema:**

[ScreenSchemeId](../schemas/Screen/ScreenSchemeId.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
