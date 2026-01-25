# PUT /rest/api/3/screenscheme/{screenSchemeId}

**Resource:** [Screen schemes](../resources/Screen-schemes.md)
**Update screen scheme**
**Operation ID:** `updateScreenScheme`

Updates a screen scheme. Only screen schemes used in classic projects can be updated.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenSchemeId` | path | string | Yes | The ID of the screen scheme. |

## Request Body

The screen scheme update details.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateScreenSchemeDetails](../schemas/Update/UpdateScreenSchemeDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the screen scheme or a screen used as one of the screen types is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
