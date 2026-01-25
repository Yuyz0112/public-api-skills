# CustomFieldContextDefaultValueSingleVersionPicker

The default value for a version picker custom field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes |  |
| `versionId` | string | Yes | The ID of the default version. |
| `versionOrder` | string | No | The order the pickable versions are displayed in. If not provided, the released-first order is used. Available version orders are `"releasedFirst"` and `"unreleasedFirst"`. |

