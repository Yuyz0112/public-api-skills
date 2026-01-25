# PUT /rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}/mapping/default

**Resource:** [Issue type screen schemes](../resources/Issue-type-screen-schemes.md)
**Update issue type screen scheme default screen scheme**
**Operation ID:** `updateDefaultScreenScheme`

Updates the default screen scheme of an issue type screen scheme. The default screen scheme is used for all unmapped issue types.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeScreenSchemeId` | path | string | Yes | The ID of the issue type screen scheme. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateDefaultScreenScheme](../schemas/Update/UpdateDefaultScreenScheme.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type screen scheme or the screen scheme is not found, or the screen scheme isn't used in classic projects. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
