# JsonTypeBean

The schema of a field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `configuration` | object | No | If the field is a custom field, the configuration of the field. |
| `custom` | string | No | If the field is a custom field, the URI of the field. |
| `customId` | integer (int64) | No | If the field is a custom field, the custom ID of the field. |
| `items` | string | No | When the data type is an array, the name of the field items within the array. |
| `system` | string | No | If the field is a system field, the name of the field. |
| `type` | string | Yes | The data type of the field. |

