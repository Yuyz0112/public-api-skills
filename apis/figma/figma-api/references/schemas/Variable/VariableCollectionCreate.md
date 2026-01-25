# VariableCollectionCreate

An object that contains details about creating a `VariableCollection`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: CREATE | Yes | The action to perform for the variable collection. |
| `id` | string | No | A temporary id for this variable collection. |
| `name` | string | Yes | The name of this variable collection. |
| `initialModeId` | string | No | The initial mode refers to the mode that is created by default. You can set a temporary id here, in order to reference this mode later in this request. |
| `hiddenFromPublishing` | boolean | No | Whether this variable collection is hidden when publishing the current file as a library. |
| `parentVariableCollectionId` | string | No | The id of the parent variable collection that this variable collection is extending from. |
| `initialModeIdToParentModeIdMapping` | object | No | Maps inherited modes from the parent variable collection to the initial mode ids on the extended variable collection. |

