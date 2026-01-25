# smartshield_smart_shield_settings_patch_response

A consolidated object containing settings from multiple APIs for partial updates.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `smart_tiered_cache` | object | Yes |  |

## Nested Fields

### `smart_tiered_cache`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `editable` | boolean | No | Whether the setting is editable. |
| `id` | string | No | The id of the Smart Tiered Cache setting. |
| `modified_on` | string | No | The last time the setting was modified. |
| `value` | enum: on, off | No | Specifies the enablement value of Tiered Cache. |

