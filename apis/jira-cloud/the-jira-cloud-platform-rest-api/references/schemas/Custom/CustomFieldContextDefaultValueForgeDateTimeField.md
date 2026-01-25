# CustomFieldContextDefaultValueForgeDateTimeField

The default value for a Forge date time custom field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `contextId` | string | Yes | The ID of the context. |
| `dateTime` | string | No | The default date-time in ISO format. Ignored if `useCurrent` is true. |
| `type` | string | Yes |  |
| `useCurrent` | boolean | No | Whether to use the current date. |

