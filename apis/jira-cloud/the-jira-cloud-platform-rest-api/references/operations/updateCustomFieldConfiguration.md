# PUT /rest/api/3/app/field/{fieldIdOrKey}/context/configuration

**Resource:** [Issue custom field configuration (apps)](../resources/Issue-custom-field-configuration-apps.md)
**Update custom field configurations**
**Operation ID:** `updateCustomFieldConfiguration`

Update the configuration for contexts of a custom field of a [type](https://developer.atlassian.com/platform/forge/manifest-reference/modules/jira-custom-field-type/) created by a [Forge app](https://developer.atlassian.com/platform/forge/).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). Jira permissions are not required for the Forge app that created the custom field type.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldIdOrKey` | path | string | Yes | The ID or key of the custom field, for example `customfield_10000`. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CustomFieldConfigurations](../schemas/Custom/CustomFieldConfigurations.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user is not a Jira admin or the request is not authenticated as from the app that provided the field. |
| 404 | Returned if the custom field is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
