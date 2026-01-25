# LayoutGrid

Guides to align and place objects within a frames.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pattern` | enum: COLUMNS, ROWS, GRID | Yes | Orientation of the grid as a string enum

- `COLUMNS`: Vertical grid
- `ROWS`: Horizontal grid
- `GRID`: Square grid |
| `sectionSize` | number | Yes | Width of column grid or height of row grid or square grid spacing. |
| `visible` | boolean | Yes | Is the grid currently visible? |
| `color` | [RGBA](RGBA.md) | Yes |  |
| `alignment` | enum: MIN, MAX, STRETCH... | Yes | Positioning of grid as a string enum

- `MIN`: Grid starts at the left or top of the frame
- `MAX`: Grid starts at the right or bottom of the frame
- `STRETCH`: Grid is stretched to fit the frame
- `CENTER`: Grid is center aligned |
| `gutterSize` | number | Yes | Spacing in between columns and rows |
| `offset` | number | Yes | Spacing before the first column or row |
| `count` | number | Yes | Number of columns or rows |
| `boundVariables` | object | No | The variables bound to a particular field on this layout grid |

## Nested Fields

### `boundVariables`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gutterSize` | [VariableAlias](VariableAlias.md) | No |  |
| `numSections` | [VariableAlias](VariableAlias.md) | No |  |
| `sectionSize` | [VariableAlias](VariableAlias.md) | No |  |
| `offset` | [VariableAlias](VariableAlias.md) | No |  |

