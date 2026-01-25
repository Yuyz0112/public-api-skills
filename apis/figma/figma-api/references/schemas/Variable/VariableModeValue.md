# VariableModeValue

An object that represents a value for a given mode of a variable. All properties are required.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `variableId` | string | Yes | The target variable. You can use the temporary id of a variable. |
| `modeId` | string | Yes | Must correspond to a mode in the variable collection that contains the target variable. |
| `value` | [VariableValue](VariableValue.md) | Yes |  |

