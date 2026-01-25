# MinimalStrokesTrait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `strokes` | Paint[] | No | An array of stroke paints applied to the node. |
| `strokeWeight` | number | No | The weight of strokes on the node. |
| `strokeAlign` | enum: INSIDE, OUTSIDE, CENTER | No | Position of stroke relative to vector outline, as a string enum

- `INSIDE`: stroke drawn inside the shape boundary
- `OUTSIDE`: stroke drawn outside the shape boundary
- `CENTER`: stroke drawn centered along the shape boundary |
| `strokeJoin` | enum: MITER, BEVEL, ROUND | No | A string enum with value of "MITER", "BEVEL", or "ROUND", describing how corners in vector paths are rendered. |
| `strokeDashes` | number[] | No | An array of floating point numbers describing the pattern of dash length and gap lengths that the vector stroke will use when drawn.

For example a value of [1, 2] indicates that the stroke will be drawn with a dash of length 1 followed by a gap of length 2, repeated. |

