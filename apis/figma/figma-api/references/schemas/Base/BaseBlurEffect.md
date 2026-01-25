# BaseBlurEffect

Base properties shared by all blur effects

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: LAYER_BLUR, BACKGROUND_BLUR | Yes | A string literal representing the effect's type. Always check the type before reading other properties. |
| `visible` | boolean | Yes | Whether this blur is active. |
| `radius` | number | Yes | Radius of the blur effect |
| `boundVariables` | object | No | The variables bound to a particular field on this blur effect |

## Nested Fields

### `boundVariables`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `radius` | [VariableAlias](VariableAlias.md) | No |  |

