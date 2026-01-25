# HasFramePropertiesTrait

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clipsContent` | boolean | Yes | Whether or not this node clip content outside of its bounds |
| `background` | Paint[] | No | Background of the node. This is deprecated, as backgrounds for frames are now in the `fills` field. |
| `backgroundColor` | [RGBA](RGBA.md) | No |  |
| `layoutGrids` | LayoutGrid[] | No | An array of layout grids attached to this node (see layout grids section for more details). GROUP nodes do not have this attribute |
| `overflowDirection` | enum: HORIZONTAL_SCROLLING, VERTICAL_SCROLLING, HORIZONTAL_AND_VERTICAL_SCROLLING... | No | Whether a node has primary axis scrolling, horizontal or vertical. |
| `layoutMode` | enum: NONE, HORIZONTAL, VERTICAL... | No | Whether this layer uses auto-layout to position its children. |
| `primaryAxisSizingMode` | enum: FIXED, AUTO | No | Whether the primary axis has a fixed length (determined by the user) or an automatic length (determined by the layout engine). This property is only applicable for auto-layout frames. |
| `counterAxisSizingMode` | enum: FIXED, AUTO | No | Whether the counter axis has a fixed length (determined by the user) or an automatic length (determined by the layout engine). This property is only applicable for auto-layout frames. |
| `primaryAxisAlignItems` | enum: MIN, CENTER, MAX... | No | Determines how the auto-layout frame's children should be aligned in the primary axis direction. This property is only applicable for auto-layout frames. |
| `counterAxisAlignItems` | enum: MIN, CENTER, MAX... | No | Determines how the auto-layout frame's children should be aligned in the counter axis direction. This property is only applicable for auto-layout frames. |
| `paddingLeft` | number | No | The padding between the left border of the frame and its children. This property is only applicable for auto-layout frames. |
| `paddingRight` | number | No | The padding between the right border of the frame and its children. This property is only applicable for auto-layout frames. |
| `paddingTop` | number | No | The padding between the top border of the frame and its children. This property is only applicable for auto-layout frames. |
| `paddingBottom` | number | No | The padding between the bottom border of the frame and its children. This property is only applicable for auto-layout frames. |
| `itemSpacing` | number | No | The distance between children of the frame. Can be negative. This property is only applicable for auto-layout frames. |
| `itemReverseZIndex` | boolean | No | Determines the canvas stacking order of layers in this frame. When true, the first layer will be draw on top. This property is only applicable for auto-layout frames. |
| `strokesIncludedInLayout` | boolean | No | Determines whether strokes are included in layout calculations. When true, auto-layout frames behave like css "box-sizing: border-box". This property is only applicable for auto-layout frames. |
| `layoutWrap` | enum: NO_WRAP, WRAP | No | Whether this auto-layout frame has wrapping enabled. |
| `counterAxisSpacing` | number | No | The distance between wrapped tracks of an auto-layout frame. This property is only applicable for auto-layout frames with `layoutWrap: "WRAP"` |
| `counterAxisAlignContent` | enum: AUTO, SPACE_BETWEEN | No | Determines how the auto-layout frame’s wrapped tracks should be aligned in the counter axis direction. This property is only applicable for auto-layout frames with `layoutWrap: "WRAP"`. |

