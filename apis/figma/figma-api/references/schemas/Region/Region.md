# Region

Position of a region comment on the canvas.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `x` | number | Yes | X coordinate of the position. |
| `y` | number | Yes | Y coordinate of the position. |
| `region_height` | number | Yes | The height of the comment region. Must be greater than 0. |
| `region_width` | number | Yes | The width of the comment region. Must be greater than 0. |
| `comment_pin_corner` | enum: top-left, top-right, bottom-left... | No | The corner of the comment region to pin to the node's corner as a string enum. |

