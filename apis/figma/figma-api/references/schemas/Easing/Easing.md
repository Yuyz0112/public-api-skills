# Easing

Describes an easing curve.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | [EasingType](EasingType.md) | Yes |  |
| `easingFunctionCubicBezier` | object | No | A cubic bezier curve that defines the easing. |
| `easingFunctionSpring` | object | No | A spring function that defines the easing. |

## Nested Fields

### `easingFunctionCubicBezier`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `x1` | number | Yes | The x component of the first control point. |
| `y1` | number | Yes | The y component of the first control point. |
| `x2` | number | Yes | The x component of the second control point. |
| `y2` | number | Yes | The y component of the second control point. |

### `easingFunctionSpring`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mass` | number | Yes |  |
| `stiffness` | number | Yes |  |
| `damping` | number | Yes |  |

