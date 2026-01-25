# FrameInfo

Data on the frame a component resides in.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `nodeId` | string | No | The ID of the frame node within the file. |
| `name` | string | No | The name of the frame node. |
| `backgroundColor` | string | No | The background color of the frame node. |
| `pageId` | string | Yes | The ID of the page containing the frame node. |
| `pageName` | string | Yes | The name of the page containing the frame node. |
| `containingStateGroup` | any | No | Deprecated - Use containingComponentSet instead. |
| `containingComponentSet` | any | No | The component set node that contains the frame node. |

