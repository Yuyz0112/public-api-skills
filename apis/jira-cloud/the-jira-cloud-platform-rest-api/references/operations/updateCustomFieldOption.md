# PUT /rest/api/3/field/{fieldId}/context/{contextId}/option

**Resource:** [Issue custom field options](../resources/Issue-custom-field-options.md)
**Update custom field options (context)**
**Operation ID:** `updateCustomFieldOption`

Updates the options of a custom field.

If any of the options are not found, no options are updated. Options where the values in the request match the current values aren't updated and aren't reported in the response.

Note that this operation **only works for issue field select list options created in Jira or using operations from the [Issue custom field options](#api-group-Issue-custom-field-options) resource**, it cannot be used with issue field select list options created by Connect apps.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `contextId` | path | integer (int64) | Yes | The ID of the context. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BulkCustomFieldOptionUpdateRequest](../schemas/Bulk/BulkCustomFieldOptionUpdateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the field, context, or one or more options is not found. |

**Success Response Schema:**

[CustomFieldUpdatedContextOptionsList](../schemas/Custom/CustomFieldUpdatedContextOptionsList.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
