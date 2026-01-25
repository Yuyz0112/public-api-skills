# PUT /rest/api/3/fieldconfigurationscheme/project

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Assign field configuration scheme to project**
**Operation ID:** `assignFieldConfigurationSchemeToProject`

Assigns a field configuration scheme to a project. If the field configuration scheme ID is `null`, the operation assigns the default field configuration scheme.

Field configuration schemes can only be assigned to classic projects.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [FieldConfigurationSchemeProjectAssociation](../schemas/Field/FieldConfigurationSchemeProjectAssociation.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the project is not a classic project. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permissions. |
| 404 | Returned if the project is missing. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
