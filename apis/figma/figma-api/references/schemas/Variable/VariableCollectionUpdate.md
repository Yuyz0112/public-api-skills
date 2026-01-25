# VariableCollectionUpdate

An object that contains details about updating a `VariableCollection`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: UPDATE | Yes | The action to perform for the variable collection. |
| `id` | string | Yes | The id of the variable collection to update. |
| `name` | string | No | The name of this variable collection. |
| `hiddenFromPublishing` | boolean | No | Whether this variable collection is hidden when publishing the current file as a library. |

