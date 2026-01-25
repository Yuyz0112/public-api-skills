# PublishedVariable

A Variable is a single design token that defines values for each of the modes in its VariableCollection. These values can be applied to various kinds of design properties.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The unique identifier of this variable. |
| `subscribed_id` | string | Yes | The ID of the variable that is used by subscribing files. This ID changes every time the variable is modified and published. |
| `name` | string | Yes | The name of this variable. |
| `key` | string | Yes | The key of this variable. |
| `variableCollectionId` | string | Yes | The id of the variable collection that contains this variable. |
| `resolvedDataType` | [VariableResolvedDataType](VariableResolvedDataType.md) | Yes |  |
| `updatedAt` | string (date-time) | Yes | The UTC ISO 8601 time at which the variable was last updated. |

