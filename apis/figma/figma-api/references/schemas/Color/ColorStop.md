# ColorStop

A single color stop with its position along the gradient axis, color, and bound variables if any

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `position` | number | Yes | Value between 0 and 1 representing position along gradient axis. |
| `color` | [RGBA](RGBA.md) | Yes |  |
| `boundVariables` | object | No | The variables bound to a particular gradient stop |

## Nested Fields

### `boundVariables`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `color` | [VariableAlias](VariableAlias.md) | No |  |

