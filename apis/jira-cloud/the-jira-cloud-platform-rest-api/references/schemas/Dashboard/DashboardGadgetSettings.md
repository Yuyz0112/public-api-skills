# DashboardGadgetSettings

Details of the settings for a dashboard gadget.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `color` | string | No | The color of the gadget. Should be one of `blue`, `red`, `yellow`, `green`, `cyan`, `purple`, `gray`, or `white`. |
| `ignoreUriAndModuleKeyValidation` | boolean | No | Whether to ignore the validation of module key and URI. For example, when a gadget is created that is a part of an application that isn't installed. |
| `moduleKey` | string | No | The module key of the gadget type. Can't be provided with `uri`. |
| `position` | any | No | The position of the gadget. When the gadget is placed into the position, other gadgets in the same column are moved down to accommodate it. |
| `title` | string | No | The title of the gadget. |
| `uri` | string | No | The URI of the gadget type. Can't be provided with `moduleKey`. |

