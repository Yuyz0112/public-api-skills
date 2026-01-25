# BaseShadowEffect

Base properties shared by all shadow effects

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `color` | [RGBA](RGBA.md) | Yes |  |
| `blendMode` | [BlendMode](BlendMode.md) | Yes |  |
| `offset` | [Vector](Vector.md) | Yes |  |
| `radius` | number | Yes | Radius of the blur effect (applies to shadows as well) |
| `spread` | number | No | The distance by which to expand (or contract) the shadow.

For drop shadows, a positive `spread` value creates a shadow larger than the node, whereas a negative value creates a shadow smaller than the node.

For inner shadows, a positive `spread` value contracts the shadow. Spread values are only accepted on rectangles and ellipses, or on frames, components, and instances with visible fill paints and `clipsContent` enabled. When left unspecified, the default value is 0. |
| `visible` | boolean | Yes | Whether this shadow is visible. |
| `boundVariables` | object | No | The variables bound to a particular field on this shadow effect |

## Nested Fields

### `boundVariables`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `radius` | [VariableAlias](VariableAlias.md) | No |  |
| `spread` | [VariableAlias](VariableAlias.md) | No |  |
| `color` | [VariableAlias](VariableAlias.md) | No |  |
| `offsetX` | [VariableAlias](VariableAlias.md) | No |  |
| `offsetY` | [VariableAlias](VariableAlias.md) | No |  |

