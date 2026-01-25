# VariableModeDelete

An object that contains details about deleting a `VariableMode`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: DELETE | Yes | The action to perform for the variable mode. |
| `id` | string | Yes | The id of the variable mode to delete. Modes cannot be deleted on extended collections unless its parent mode has been deleted. |

