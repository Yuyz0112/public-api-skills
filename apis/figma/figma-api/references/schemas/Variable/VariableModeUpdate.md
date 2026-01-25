# VariableModeUpdate

An object that contains details about updating a `VariableMode`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: UPDATE | Yes | The action to perform for the variable mode. |
| `id` | string | Yes | The id of the variable mode to update. |
| `name` | string | No | The name of this variable mode. |
| `variableCollectionId` | string | Yes | The variable collection that contains the mode. Modes cannot be updated on extended collections. |

