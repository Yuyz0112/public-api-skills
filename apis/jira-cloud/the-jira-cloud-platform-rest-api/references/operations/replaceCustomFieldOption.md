# DELETE /rest/api/3/field/{fieldId}/context/{contextId}/option/{optionId}/issue

**Resource:** [Issue custom field options](../resources/Issue-custom-field-options.md)
**Replace custom field options**
**Operation ID:** `replaceCustomFieldOption`

Replaces the options of a custom field.

Note that this operation **only works for issue field select list options created in Jira or using operations from the [Issue custom field options](#api-group-Issue-custom-field-options) resource**, it cannot be used with issue field select list options created by Connect or Forge apps.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `replaceWith` | query | integer (int64) | No | The ID of the option that will replace the currently selected option. |
| `jql` | query | string | No | A JQL query that specifies the issues to be updated. For example, *project=10000*. |
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `optionId` | path | integer (int64) | Yes | The ID of the option to be deselected. |
| `contextId` | path | integer (int64) | Yes | The ID of the context. |

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the long-running task to deselect the option is started. |
| 400 | Returned if the request is not valid. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the field is not found or does not support options, or the options to be replaced are not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
