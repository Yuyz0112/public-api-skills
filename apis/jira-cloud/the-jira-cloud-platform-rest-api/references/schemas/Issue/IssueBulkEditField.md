# IssueBulkEditField

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | Description of the field. |
| `fieldOptions` | IssueBulkOperationsFieldOption[] | No | A list of options related to the field, applicable in contexts where multiple selections are allowed. |
| `id` | string | No | The unique ID of the field. |
| `isRequired` | boolean | No | Indicates whether the field is mandatory for the operation. |
| `multiSelectFieldOptions` | string[] | No | Specifies supported actions (like add, replace, remove) on multi-select fields via an enum. |
| `name` | string | No | The display name of the field. |
| `searchUrl` | string | No | A URL to fetch additional data for the field |
| `type` | string | No | The type of the field. |
| `unavailableMessage` | string | No | A message indicating why the field is unavailable for editing. |

