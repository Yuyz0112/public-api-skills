# VariableUpdate

An object that contains details about updating a `Variable`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: UPDATE | Yes | The action to perform for the variable. |
| `id` | string | Yes | The id of the variable to update. |
| `name` | string | No | The name of this variable. |
| `description` | string | No | The description of this variable. |
| `hiddenFromPublishing` | boolean | No | Whether this variable is hidden when publishing the current file as a library. |
| `scopes` | VariableScope[] | No | An array of scopes in the UI where this variable is shown. Setting this property will show/hide this variable in the variable picker UI for different fields. |
| `codeSyntax` | [VariableCodeSyntax](VariableCodeSyntax.md) | No |  |

