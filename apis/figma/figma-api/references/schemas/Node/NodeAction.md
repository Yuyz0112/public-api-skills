# NodeAction

An action that navigates to a specific node in the Figma viewer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: NODE | Yes |  |
| `destinationId` | string,null | Yes |  |
| `navigation` | [Navigation](Navigation.md) | Yes |  |
| `transition` | any | Yes |  |
| `preserveScrollPosition` | boolean | No | Whether the scroll offsets of any scrollable elements in the current screen or overlay are preserved when navigating to the destination. This is applicable only if the layout of both the current frame and its destination are the same. |
| `overlayRelativePosition` | [Vector](Vector.md) | No |  |
| `resetVideoPosition` | boolean | No | When true, all videos within the destination frame will reset their memorized playback position to 00:00 before starting to play. |
| `resetScrollPosition` | boolean | No | Whether the scroll offsets of any scrollable elements in the current screen or overlay reset when navigating to the destination. This is applicable only if the layout of both the current frame and its destination are the same. |
| `resetInteractiveComponents` | boolean | No | Whether the state of any interactive components in the current screen or overlay reset when navigating to the destination. This is applicable if there are interactive components in the destination frame. |

