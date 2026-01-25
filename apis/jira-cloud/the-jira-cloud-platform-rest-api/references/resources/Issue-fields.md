# Issue fields

This resource represents issue fields, both system and custom fields. Use it to get fields, field configurations, and create custom fields.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/field` | Get fields | [View](../operations/getFields.md) |
| POST | `/rest/api/3/field` | Create custom field | [View](../operations/createCustomField.md) |
| GET | `/rest/api/3/field/search` | Get fields paginated | [View](../operations/getFieldsPaginated.md) |
| GET | `/rest/api/3/field/search/trashed` | Get fields in trash paginated | [View](../operations/getTrashedFieldsPaginated.md) |
| PUT | `/rest/api/3/field/{fieldId}` | Update custom field | [View](../operations/updateCustomField.md) |
| GET | `/rest/api/3/field/{fieldId}/contexts` | Get contexts for a field | [View](../operations/getContextsForFieldDeprecated.md) |
| DELETE | `/rest/api/3/field/{id}` | Delete custom field | [View](../operations/deleteCustomField.md) |
| POST | `/rest/api/3/field/{id}/restore` | Restore custom field from trash | [View](../operations/restoreCustomField.md) |
| POST | `/rest/api/3/field/{id}/trash` | Move custom field to trash | [View](../operations/trashCustomField.md) |
| GET | `/rest/api/3/projects/fields` | Get fields for projects | [View](../operations/getProjectFields.md) |
