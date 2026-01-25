# POST /rest/api/3/fieldconfiguration

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Create field configuration**
**Operation ID:** `createFieldConfiguration`
⚠️ **Deprecated**

Deprecated, use [Field schemes](#api-group-field-schemes) which supports field association schemes.

Creates a field configuration. The field configuration is created with the same field properties as the default configuration, with all the fields being optional.

This operation can only create configurations for use in company-managed (classic) projects.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [FieldConfigurationDetails](../schemas/Field/FieldConfigurationDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[FieldConfiguration](../schemas/Field/FieldConfiguration.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
