# POST /rest/api/3/field/{fieldId}/context/{contextId}/option

**Resource:** [Issue custom field options](../resources/Issue-custom-field-options.md)
**Create custom field options (context)**
**Operation ID:** `createCustomFieldOption`

Creates options and, where the custom select field is of the type Select List (cascading), cascading options for a custom select field. The options are added to a context of the field.

The maximum number of options that can be created per request is 1000 and each field can have a maximum of 10000 options.

This operation works for custom field options created in Jira or the operations from this resource. **To work with issue field select list options created for Connect apps use the [Issue custom field options (apps)](#api-group-issue-custom-field-options--apps-) operations.**

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `contextId` | path | integer (int64) | Yes | The ID of the context. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BulkCustomFieldOptionCreateRequest](../schemas/Bulk/BulkCustomFieldOptionCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the custom field is not found or the context doesn't match the custom field. |

**Success Response Schema:**

[CustomFieldCreatedContextOptionsList](../schemas/Custom/CustomFieldCreatedContextOptionsList.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
