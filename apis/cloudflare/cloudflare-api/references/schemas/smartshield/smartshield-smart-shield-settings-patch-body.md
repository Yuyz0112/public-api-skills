# smartshield_smart_shield_settings_patch_body

The patch body for Smart Shield.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cache_reserve` | object | No |  |
| `regional_tiered_cache` | object | No |  |
| `smart_routing` | object | No |  |
| `smart_tiered_cache` | object | No |  |

## Nested Fields

### `cache_reserve`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | enum: on, off | No | Specifies the enablement value of Cache Reserve. |

### `regional_tiered_cache`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | enum: on, off | No | Specifies the enablement value of Regional Tiered Cache. |

### `smart_routing`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | enum: on, off | No | Specifies the enablement value of Smart Routing. |

### `smart_tiered_cache`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | enum: on, off | No | Specifies the enablement value of Smart Tiered Cache. |

