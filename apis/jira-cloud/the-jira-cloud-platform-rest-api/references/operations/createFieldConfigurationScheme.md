# POST /rest/api/3/fieldconfigurationscheme

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Create field configuration scheme**
**Operation ID:** `createFieldConfigurationScheme`

Creates a field configuration scheme.

This operation can only create field configuration schemes used in company-managed (classic) projects.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

The details of the field configuration scheme.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateFieldConfigurationSchemeDetails](../schemas/Update/UpdateFieldConfigurationSchemeDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permissions. |

**Success Response Schema:**

[FieldConfigurationScheme](../schemas/Field/FieldConfigurationScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
