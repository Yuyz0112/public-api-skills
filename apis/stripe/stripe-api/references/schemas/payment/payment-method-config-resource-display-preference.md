# payment_method_config_resource_display_preference

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `overridable` | boolean | No | For child configs, whether or not the account's preference will be observed. If `false`, the parent configuration's default is used. |
| `preference` | enum: none, off, on | Yes | The account's display preference. |
| `value` | enum: off, on | Yes | The effective display preference value. |

