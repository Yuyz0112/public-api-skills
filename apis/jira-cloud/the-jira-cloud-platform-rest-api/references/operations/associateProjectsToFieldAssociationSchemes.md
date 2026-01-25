# PUT /rest/api/3/config/fieldschemes/projects

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Associate projects to field schemes**
**Operation ID:** `associateProjectsToFieldAssociationSchemes`

Associate projects to field association schemes.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the association was successful. |
| 204 | The request completed successfully. No additional content will be sent in the response. |
| 207 | Returned if the association was partially successful. |
| 400 | Returned if the request is invalid. If request is malformed, returns a collection of errors. If request is well-formed but contains invalid scheme or project IDs, returns failure details. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions |

**Success Response Schema:**

[FieldSchemeToProjectsResponse](../schemas/Field/FieldSchemeToProjectsResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
