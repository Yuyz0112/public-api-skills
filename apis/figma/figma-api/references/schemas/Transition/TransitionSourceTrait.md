# TransitionSourceTrait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `transitionNodeID` | string | No | Node ID of node to transition to in prototyping |
| `transitionDuration` | number | No | The duration of the prototyping transition on this node (in milliseconds). This will override the default transition duration on the prototype, for this node. |
| `transitionEasing` | [EasingType](EasingType.md) | No |  |
| `interactions` | Interaction[] | No |  |

