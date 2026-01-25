# FieldReferenceData

Details of a field that can be used in advanced searches.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auto` | enum: true, false | No | Whether the field provide auto-complete suggestions. |
| `cfid` | string | No | If the item is a custom field, the ID of the custom field. |
| `deprecated` | enum: true, false | No | Whether this field has been deprecated. |
| `deprecatedSearcherKey` | string | No | The searcher key of the field, only passed when the field is deprecated. |
| `displayName` | string | No | The display name contains the following:

 *  for system fields, the field name. For example, `Summary`.
 *  for collapsed custom fields, the field name followed by a hyphen and then the field name and field type. For example, `Component - Component[Dropdown]`.
 *  for other custom fields, the field name followed by a hyphen and then the custom field ID. For example, `Component - cf[10061]`. |
| `operators` | string[] | No | The valid search operators for the field. |
| `orderable` | enum: true, false | No | Whether the field can be used in a query's `ORDER BY` clause. |
| `searchable` | enum: true, false | No | Whether the content of this field can be searched. |
| `types` | string[] | No | The data types of items in the field. |
| `value` | string | No | The field identifier. |

