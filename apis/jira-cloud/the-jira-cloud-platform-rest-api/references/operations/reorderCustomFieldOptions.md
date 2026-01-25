# PUT /rest/api/3/field/{fieldId}/context/{contextId}/option/move

**Resource:** [Issue custom field options](../resources/Issue-custom-field-options.md)
**Reorder custom field options (context)**
**Operation ID:** `reorderCustomFieldOptions`

Changes the order of custom field options or cascading options in a context.

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

**Schema:** [OrderOfCustomFieldOptions](../schemas/Order/OrderOfCustomFieldOptions.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if options are reordered. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the field, the context, or one or more of the options is not found.. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
