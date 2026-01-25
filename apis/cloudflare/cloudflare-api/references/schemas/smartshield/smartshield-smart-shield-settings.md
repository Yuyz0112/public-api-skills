# smartshield_smart_shield_settings

A consolidated object containing settings from multiple APIs for partial updates.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cache_reserve` | any | No |  |
| `regional_tiered_cache` | object | No |  |
| `smart_routing` | object | No |  |
| `smart_tiered_cache` | object | No |  |

## Nested Fields

### `regional_tiered_cache`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `editable` | boolean | No | Whether the setting is editable. |
| `id` | string | No | The id of the Regional Tiered Cache setting. |
| `value` | enum: on, off | No | Specifies the enablement value of Cache Reserve. |

### `smart_routing`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `editable` | boolean | No | Whether the setting is editable. |
| `id` | string | No | The id of the Smart Routing setting. |
| `value` | enum: on, off | No | Specifies the enablement value of Argo Smart Routing. |

### `smart_tiered_cache`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `editable` | boolean | No | Whether the setting is editable. |
| `id` | string | No | The id of the Smart Tiered Cache setting. |
| `modified_on` | string | No | The last time the setting was modified. |
| `value` | enum: on, off | No | Specifies the enablement value of Tiered Cache. |

