# CornerTrait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cornerRadius` | number | No | Radius of each corner if a single radius is set for all corners |
| `cornerSmoothing` | number | No | A value that lets you control how "smooth" the corners are. Ranges from 0 to 1. 0 is the default and means that the corner is perfectly circular. A value of 0.6 means the corner matches the iOS 7 "squircle" icon shape. Other values produce various other curves. |
| `rectangleCornerRadii` | number[] | No | Array of length 4 of the radius of each corner of the frame, starting in the top left and proceeding clockwise.

Values are given in the order top-left, top-right, bottom-right, bottom-left. |

