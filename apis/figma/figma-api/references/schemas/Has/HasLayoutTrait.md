# HasLayoutTrait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `absoluteBoundingBox` | any | Yes | Bounding box of the node in absolute space coordinates. |
| `absoluteRenderBounds` | any | Yes | The actual bounds of a node accounting for drop shadows, thick strokes, and anything else that may fall outside the node's regular bounding box defined in `x`, `y`, `width`, and `height`. The `x` and `y` inside this property represent the absolute position of the node on the page. This value will be `null` if the node is invisible. |
| `preserveRatio` | boolean | No | Keep height and width constrained to same ratio. |
| `constraints` | [LayoutConstraint](LayoutConstraint.md) | No |  |
| `relativeTransform` | [Transform](Transform.md) | No |  |
| `size` | [Vector](Vector.md) | No |  |
| `layoutAlign` | enum: INHERIT, STRETCH, MIN... | No | 
Determines if the layer should stretch along the parent's counter axis. This property is only provided for direct children of auto-layout frames.

- `INHERIT`
- `STRETCH`

In previous versions of auto layout, determined how the layer is aligned inside an auto-layout frame. This property is only provided for direct children of auto-layout frames.

- `MIN`
- `CENTER`
- `MAX`
- `STRETCH`

In horizontal auto-layout frames, "MIN" and "MAX" correspond to "TOP" and "BOTTOM". In vertical auto-layout frames, "MIN" and "MAX" correspond to "LEFT" and "RIGHT". |
| `layoutGrow` | enum: 0, 1 | No | This property is applicable only for direct children of auto-layout frames, ignored otherwise. Determines whether a layer should stretch along the parent's primary axis. A `0` corresponds to a fixed size and `1` corresponds to stretch. |
| `layoutPositioning` | enum: AUTO, ABSOLUTE | No | Determines whether a layer's size and position should be determined by auto-layout settings or manually adjustable. |
| `minWidth` | number | No | The minimum width of the frame. This property is only applicable for auto-layout frames or direct children of auto-layout frames. |
| `maxWidth` | number | No | The maximum width of the frame. This property is only applicable for auto-layout frames or direct children of auto-layout frames. |
| `minHeight` | number | No | The minimum height of the frame. This property is only applicable for auto-layout frames or direct children of auto-layout frames. |
| `maxHeight` | number | No | The maximum height of the frame. This property is only applicable for auto-layout frames or direct children of auto-layout frames. |
| `layoutSizingHorizontal` | enum: FIXED, HUG, FILL | No | The horizontal sizing setting on this auto-layout frame or frame child.
- `FIXED`
- `HUG`: only valid on auto-layout frames and text nodes
- `FILL`: only valid on auto-layout frame children |
| `layoutSizingVertical` | enum: FIXED, HUG, FILL | No | The vertical sizing setting on this auto-layout frame or frame child.
- `FIXED`
- `HUG`: only valid on auto-layout frames and text nodes
- `FILL`: only valid on auto-layout frame children |
| `gridRowCount` | number | No | The number of rows in the grid layout. This property is only applicable for auto-layout frames with `layoutMode: "GRID"`. |
| `gridColumnCount` | number | No | The number of columns in the grid layout. This property is only applicable for auto-layout frames with `layoutMode: "GRID"`. |
| `gridRowGap` | number | No | The distance between rows in the grid layout. This property is only applicable for auto-layout frames with `layoutMode: "GRID"`. |
| `gridColumnGap` | number | No | The distance between columns in the grid layout. This property is only applicable for auto-layout frames with `layoutMode: "GRID"`. |
| `gridColumnsSizing` | string | No | The string for the CSS grid-template-columns property. This property is only applicable for auto-layout frames with `layoutMode: "GRID"`. |
| `gridRowsSizing` | string | No | The string for the CSS grid-template-rows property. This property is only applicable for auto-layout frames with `layoutMode: "GRID"`. |
| `gridChildHorizontalAlign` | enum: AUTO, MIN, CENTER... | No | Determines how a GRID frame's child should be aligned in the horizontal direction within its grid area. This property is only applicable for direct children of frames with `layoutMode: "GRID"`. |
| `gridChildVerticalAlign` | enum: AUTO, MIN, CENTER... | No | Determines how a GRID frame's child should be aligned in the vertical direction within its grid area. This property is only applicable for direct children of frames with `layoutMode: "GRID"`. |
| `gridRowSpan` | number | No | The number of rows that a GRID frame's child should span. This property is only applicable for direct children of frames with `layoutMode: "GRID"`. |
| `gridColumnSpan` | number | No | The number of columns that a GRID frame's child should span. This property is only applicable for direct children of frames with `layoutMode: "GRID"`. |
| `gridRowAnchorIndex` | number | No | The index of the row that a GRID frame's child should be anchored to. This property is only applicable for direct children of frames with `layoutMode: "GRID"`. |
| `gridColumnAnchorIndex` | number | No | The index of the column that a GRID frame's child should be anchored to. This property is only applicable for direct children of frames with `layoutMode: "GRID"`. |

