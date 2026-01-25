# DirectionalTransition

Describes an animation used when navigating in a prototype.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: MOVE_IN, MOVE_OUT, PUSH... | Yes |  |
| `direction` | enum: LEFT, RIGHT, TOP... | Yes |  |
| `duration` | number | Yes | The duration of the transition in milliseconds. |
| `easing` | [Easing](Easing.md) | Yes |  |
| `matchLayers` | boolean | No | When the transition `type` is `"SMART_ANIMATE"` or when `matchLayers` is `true`, then the transition will be performed using smart animate, which attempts to match corresponding layers an interpolate other properties during the animation. |

