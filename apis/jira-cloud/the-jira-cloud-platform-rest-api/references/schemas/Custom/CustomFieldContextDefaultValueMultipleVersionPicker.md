# CustomFieldContextDefaultValueMultipleVersionPicker

The default value for a multiple version picker custom field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes |  |
| `versionIds` | string[] | Yes | The IDs of the default versions. |
| `versionOrder` | string | No | The order the pickable versions are displayed in. If not provided, the released-first order is used. Available version orders are `"releasedFirst"` and `"unreleasedFirst"`. |

