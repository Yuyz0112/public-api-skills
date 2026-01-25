# PUT /rest/api/3/fieldconfiguration/{id}

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Update field configuration**
**Operation ID:** `updateFieldConfiguration`
⚠️ **Deprecated**

Deprecated, use [Field schemes](#api-group-field-schemes) which supports field association schemes.

Updates a field configuration. The name and the description provided in the request override the existing values.

This operation can only update configurations used in company-managed (classic) projects.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the field configuration. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [FieldConfigurationDetails](../schemas/Field/FieldConfigurationDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the field configuration is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
