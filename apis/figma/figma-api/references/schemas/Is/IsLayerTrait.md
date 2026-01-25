# IsLayerTrait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | A string uniquely identifying this node within the document. |
| `name` | string | Yes | The name given to the node by the user in the tool. |
| `type` | string | Yes | The type of the node |
| `visible` | boolean | No | Whether or not the node is visible on the canvas. |
| `locked` | boolean | No | If true, layer is locked and cannot be edited |
| `isFixed` | boolean | No | Whether the layer is fixed while the parent is scrolling |
| `scrollBehavior` | enum: SCROLLS, FIXED, STICKY_SCROLLS | Yes | How layer should be treated when the frame is resized |
| `rotation` | number | No | The rotation of the node, if not 0. |
| `componentPropertyReferences` | object | No | A mapping of a layer's property to component property name of component properties attached to this node. The component property name can be used to look up more information on the corresponding component's or component set's componentPropertyDefinitions. |
| `pluginData` | any | No | Data written by plugins that is visible only to the plugin that wrote it. Requires the `pluginData` to include the ID of the plugin. |
| `sharedPluginData` | any | No | Data written by plugins that is visible to all plugins. Requires the `pluginData` parameter to include the string "shared". |
| `boundVariables` | object | No | A mapping of field to the variables applied to this field. Most fields will only map to a single `VariableAlias`. However, for properties like `fills`, `strokes`, `size`, `componentProperties`, and `textRangeFills`, it is possible to have multiple variables bound to the field. |
| `explicitVariableModes` | object | No | A mapping of variable collection ID to mode ID representing the explicitly set modes for this node. |

## Nested Fields

### `boundVariables`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `size` | object | No |  |
| `individualStrokeWeights` | object | No |  |
| `characters` | [VariableAlias](VariableAlias.md) | No |  |
| `itemSpacing` | [VariableAlias](VariableAlias.md) | No |  |
| `paddingLeft` | [VariableAlias](VariableAlias.md) | No |  |
| `paddingRight` | [VariableAlias](VariableAlias.md) | No |  |
| `paddingTop` | [VariableAlias](VariableAlias.md) | No |  |
| `paddingBottom` | [VariableAlias](VariableAlias.md) | No |  |
| `visible` | [VariableAlias](VariableAlias.md) | No |  |
| `topLeftRadius` | [VariableAlias](VariableAlias.md) | No |  |
| `topRightRadius` | [VariableAlias](VariableAlias.md) | No |  |
| `bottomLeftRadius` | [VariableAlias](VariableAlias.md) | No |  |
| `bottomRightRadius` | [VariableAlias](VariableAlias.md) | No |  |
| `minWidth` | [VariableAlias](VariableAlias.md) | No |  |
| `maxWidth` | [VariableAlias](VariableAlias.md) | No |  |
| `minHeight` | [VariableAlias](VariableAlias.md) | No |  |
| `maxHeight` | [VariableAlias](VariableAlias.md) | No |  |
| `counterAxisSpacing` | [VariableAlias](VariableAlias.md) | No |  |
| `opacity` | [VariableAlias](VariableAlias.md) | No |  |
| `fontFamily` | VariableAlias[] | No |  |
| `fontSize` | VariableAlias[] | No |  |
| `fontStyle` | VariableAlias[] | No |  |
| `fontWeight` | VariableAlias[] | No |  |
| `letterSpacing` | VariableAlias[] | No |  |
| `lineHeight` | VariableAlias[] | No |  |
| `paragraphSpacing` | VariableAlias[] | No |  |
| `paragraphIndent` | VariableAlias[] | No |  |
| `fills` | VariableAlias[] | No |  |
| `strokes` | VariableAlias[] | No |  |
| `componentProperties` | object | No |  |
| `textRangeFills` | VariableAlias[] | No |  |
| `effects` | VariableAlias[] | No |  |
| `layoutGrids` | VariableAlias[] | No |  |
| `rectangleCornerRadii` | object | No |  |

#### `boundVariables.size`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `x` | [VariableAlias](VariableAlias.md) | No |  |
| `y` | [VariableAlias](VariableAlias.md) | No |  |

#### `boundVariables.individualStrokeWeights`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `top` | [VariableAlias](VariableAlias.md) | No |  |
| `bottom` | [VariableAlias](VariableAlias.md) | No |  |
| `left` | [VariableAlias](VariableAlias.md) | No |  |
| `right` | [VariableAlias](VariableAlias.md) | No |  |

#### `boundVariables.rectangleCornerRadii`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `RECTANGLE_TOP_LEFT_CORNER_RADIUS` | [VariableAlias](VariableAlias.md) | No |  |
| `RECTANGLE_TOP_RIGHT_CORNER_RADIUS` | [VariableAlias](VariableAlias.md) | No |  |
| `RECTANGLE_BOTTOM_LEFT_CORNER_RADIUS` | [VariableAlias](VariableAlias.md) | No |  |
| `RECTANGLE_BOTTOM_RIGHT_CORNER_RADIUS` | [VariableAlias](VariableAlias.md) | No |  |

