# VariableCreate

An object that contains details about creating a `Variable`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: CREATE | Yes | The action to perform for the variable. |
| `id` | string | No | A temporary id for this variable. |
| `name` | string | Yes | The name of this variable. |
| `variableCollectionId` | string | Yes | The variable collection that will contain the variable. You can use the temporary id of a variable collection. |
| `resolvedType` | [VariableResolvedDataType](VariableResolvedDataType.md) | Yes |  |
| `description` | string | No | The description of this variable. |
| `hiddenFromPublishing` | boolean | No | Whether this variable is hidden when publishing the current file as a library. |
| `scopes` | VariableScope[] | No | An array of scopes in the UI where this variable is shown. Setting this property will show/hide this variable in the variable picker UI for different fields. |
| `codeSyntax` | [VariableCodeSyntax](VariableCodeSyntax.md) | No |  |

