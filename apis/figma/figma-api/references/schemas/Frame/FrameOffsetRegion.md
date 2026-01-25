# FrameOffsetRegion

Position of a region comment relative to the frame to which it is attached.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `node_id` | string | Yes | Unique id specifying the frame. |
| `node_offset` | [Vector](Vector.md) | Yes |  |
| `region_height` | number | Yes | The height of the comment region. Must be greater than 0. |
| `region_width` | number | Yes | The width of the comment region. Must be greater than 0. |
| `comment_pin_corner` | enum: top-left, top-right, bottom-left... | No | The corner of the comment region to pin to the node's corner as a string enum. |

