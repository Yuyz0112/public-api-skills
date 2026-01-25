# FieldDetails

Details about a field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clauseNames` | string[] | No | The names that can be used to reference the field in an advanced search. For more information, see [Advanced searching - fields reference](https://confluence.atlassian.com/x/gwORLQ). |
| `custom` | boolean | No | Whether the field is a custom field. |
| `id` | string | No | The ID of the field. |
| `key` | string | No | The key of the field. |
| `name` | string | No | The name of the field. |
| `navigable` | boolean | No | Whether the field can be used as a column on the issue navigator. |
| `orderable` | boolean | No | Whether the content of the field can be used to order lists. |
| `schema` | any | No | The data schema for the field. |
| `scope` | any | No | The scope of the field. |
| `searchable` | boolean | No | Whether the content of the field can be searched. |

