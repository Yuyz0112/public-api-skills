# PUT /rest/api/3/fieldconfigurationscheme/{id}

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Update field configuration scheme**
**Operation ID:** `updateFieldConfigurationScheme`

Updates a field configuration scheme.

This operation can only update field configuration schemes used in company-managed (classic) projects.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the field configuration scheme. |

## Request Body

The details of the field configuration scheme.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateFieldConfigurationSchemeDetails](../schemas/Update/UpdateFieldConfigurationSchemeDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permissions. |
| 404 | Returned if the field configuration scheme is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
