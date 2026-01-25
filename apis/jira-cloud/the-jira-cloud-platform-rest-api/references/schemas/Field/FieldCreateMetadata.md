# FieldCreateMetadata

The metadata describing an issue field for createmeta.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowedValues` | any[] | No | The list of values allowed in the field. |
| `autoCompleteUrl` | string | No | The URL that can be used to automatically complete the field. |
| `configuration` | object | No | The configuration properties. |
| `defaultValue` | any | No | The default value of the field. |
| `fieldId` | string | Yes | The field id. |
| `hasDefaultValue` | boolean | No | Whether the field has a default value. |
| `key` | string | Yes | The key of the field. |
| `name` | string | Yes | The name of the field. |
| `operations` | string[] | Yes | The list of operations that can be performed on the field. |
| `required` | boolean | Yes | Whether the field is required. |
| `schema` | any | Yes | The data type of the field. |

