# DashboardGadget

Details of a gadget.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `color` | enum: blue, red, yellow... | Yes | The color of the gadget. Should be one of `blue`, `red`, `yellow`, `green`, `cyan`, `purple`, `gray`, or `white`. |
| `id` | integer (int64) | Yes | The ID of the gadget instance. |
| `moduleKey` | string | No | The module key of the gadget type. |
| `position` | any | Yes | The position of the gadget. |
| `title` | string | Yes | The title of the gadget. |
| `uri` | string | No | The URI of the gadget type. |

