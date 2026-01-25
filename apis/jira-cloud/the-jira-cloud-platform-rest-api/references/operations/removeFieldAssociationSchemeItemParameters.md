# DELETE /rest/api/3/config/fieldschemes/fields/parameters

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Remove field parameters**
**Operation ID:** `removeFieldAssociationSchemeItemParameters`

Remove field association parameters overrides for work types.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the removal was successful. |
| 204 | The request completed successfully. No additional content will be sent in the response. |
| 207 | Returned if the removal was partially successful. |
| 400 | Returned if the request is invalid. If request is malformed, returns a collection of errors. If request is well-formed but contains invalid scheme or project IDs, returns failure details. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
