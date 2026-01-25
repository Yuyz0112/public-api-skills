# VariableModeCreate

An object that contains details about creating a `VariableMode`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: CREATE | Yes | The action to perform for the variable mode. |
| `id` | string | No | A temporary id for this variable mode. |
| `name` | string | Yes | The name of this variable mode. |
| `variableCollectionId` | string | Yes | The variable collection that will contain the mode. You can use the temporary id of a variable collection. New modes cannot be created on extended collections. |

