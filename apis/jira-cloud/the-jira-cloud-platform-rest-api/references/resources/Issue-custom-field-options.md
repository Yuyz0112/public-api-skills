# Issue custom field options

This resource represents custom issue field select list options created in Jira or using the REST API. This resource supports the following field types:

 *  Checkboxes.
 *  Radio Buttons.
 *  Select List (single choice).
 *  Select List (multiple choices).
 *  Select List (cascading).

See [Issue custom field options (apps)](#api-group-Issue-custom-field-options--apps-) to manipulate custom issue field select list options created by a Connect app.

Use it to retrieve, create, update, order, and delete custom field options.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/customFieldOption/{id}` | Get custom field option | [View](../operations/getCustomFieldOption.md) |
| GET | `/rest/api/3/field/{fieldId}/context/{contextId}/option` | Get custom field options (context) | [View](../operations/getOptionsForContext.md) |
| PUT | `/rest/api/3/field/{fieldId}/context/{contextId}/option` | Update custom field options (context) | [View](../operations/updateCustomFieldOption.md) |
| POST | `/rest/api/3/field/{fieldId}/context/{contextId}/option` | Create custom field options (context) | [View](../operations/createCustomFieldOption.md) |
| PUT | `/rest/api/3/field/{fieldId}/context/{contextId}/option/move` | Reorder custom field options (context) | [View](../operations/reorderCustomFieldOptions.md) |
| DELETE | `/rest/api/3/field/{fieldId}/context/{contextId}/option/{optionId}` | Delete custom field options (context) | [View](../operations/deleteCustomFieldOption.md) |
| DELETE | `/rest/api/3/field/{fieldId}/context/{contextId}/option/{optionId}/issue` | Replace custom field options | [View](../operations/replaceCustomFieldOption.md) |
