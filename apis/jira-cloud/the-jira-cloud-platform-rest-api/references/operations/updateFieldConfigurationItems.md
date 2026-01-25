# PUT /rest/api/3/fieldconfiguration/{id}/fields

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Update field configuration items**
**Operation ID:** `updateFieldConfigurationItems`
⚠️ **Deprecated**

Deprecated, use [Field schemes](#api-group-field-schemes) which supports field association schemes.

Updates fields in a field configuration. The properties of the field configuration fields provided override the existing values.

This operation can only update field configurations used in company-managed (classic) projects.

The operation can set the renderer for text fields to the default text renderer (`text-renderer`) or wiki style renderer (`wiki-renderer`). However, the renderer cannot be updated for fields using the autocomplete renderer (`autocomplete-renderer`).

Hiding a field deletes it from the field configuration - deleting the required, description and renderer type values as well. As a result, hiding and unhiding will not restore the other values but use their default values.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the field configuration. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [FieldConfigurationItemsDetails](../schemas/Field/FieldConfigurationItemsDetails.md)

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
