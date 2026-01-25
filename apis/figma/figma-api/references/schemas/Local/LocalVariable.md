# LocalVariable

A Variable is a single design token that defines values for each of the modes in its VariableCollection. These values can be applied to various kinds of design properties.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The unique identifier of this variable. |
| `name` | string | Yes | The name of this variable. |
| `key` | string | Yes | The key of this variable. |
| `variableCollectionId` | string | Yes | The id of the variable collection that contains this variable. |
| `resolvedType` | [VariableResolvedDataType](VariableResolvedDataType.md) | Yes |  |
| `valuesByMode` | object | Yes | The values for each mode of this variable. |
| `remote` | boolean | Yes | Whether this variable is remote. |
| `description` | string | Yes | The description of this variable. |
| `hiddenFromPublishing` | boolean | Yes | Whether this variable is hidden when publishing the current file as a library.

If the parent `VariableCollection` is marked as `hiddenFromPublishing`, then this variable will also be hidden from publishing via the UI. `hiddenFromPublishing` is independently toggled for a variable and collection. However, both must be true for a given variable to be publishable. |
| `scopes` | VariableScope[] | Yes | An array of scopes in the UI where this variable is shown. Setting this property will show/hide this variable in the variable picker UI for different fields.

Setting scopes for a variable does not prevent that variable from being bound in other scopes (for example, via the Plugin API). This only limits the variables that are shown in pickers within the Figma UI. |
| `codeSyntax` | [VariableCodeSyntax](VariableCodeSyntax.md) | Yes |  |
| `deletedButReferenced` | boolean | No | Indicates that the variable was deleted in the editor, but the document may still contain references to the variable. References to the variable may exist through bound values or variable aliases. |

