# LocalVariableCollection

A grouping of related Variable objects each with the same modes.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The unique identifier of this variable collection. |
| `name` | string | Yes | The name of this variable collection. |
| `key` | string | Yes | The key of this variable collection. |
| `modes` | object[] | Yes | The modes of this variable collection. |
| `defaultModeId` | string | Yes | The id of the default mode. |
| `remote` | boolean | Yes | Whether this variable collection is remote. |
| `isExtension` | boolean | No | Whether this variable collection is an extension of another variable collection. |
| `parentVariableCollectionId` | string | No | The id of the parent variable collection that this variable collection is an extension of. If this variable collection is not an extension, this value will be `undefined`. |
| `rootVariableCollectionId` | string | No | The id of the root variable collection in the extension chain. This is the ID of the original (non-extended) collection at the top of the parent chain. For example, if Collection C extends B which extends A (root), then `rootVariableCollectionId` is A's ID. If this variable collection is not an extension, this value will be `undefined`. |
| `variableOverrides` | object | No | The overrides for the variables in this variable collection as a map of variable ids to a map of mode ids to variable values. |
| `hiddenFromPublishing` | boolean | Yes | Whether this variable collection is hidden when publishing the current file as a library. |
| `variableIds` | string[] | Yes | The ids of the variables in the collection. Note that the order of these variables is roughly the same as what is shown in Figma Design, however it does not account for groups. As a result, the order of these variables may not exactly reflect the exact ordering and grouping shown in the authoring UI. |

## Nested Fields

### `modes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `modeId` | string | Yes | The unique identifier of this mode. |
| `parentModeId` | string | No | The unique identifier of this mode's parent mode from the parent variable collection. This will be `undefined` if this mode does not inherit from a parent mode. |
| `name` | string | Yes | The name of this mode. |

