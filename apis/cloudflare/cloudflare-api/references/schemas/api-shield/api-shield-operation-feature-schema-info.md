# api-shield_operation_feature_schema_info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `schema_info` | object | No |  |

## Nested Fields

### `schema_info`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_schema` | object | No | Schema active on endpoint. |
| `learned_available` | boolean | No | True if a Cloudflare-provided learned schema is available for this endpoint. |
| `mitigation_action` | enum: none, log, block | No | Action taken on requests failing validation. |

#### `schema_info.active_schema`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | [api-shield_timestamp](api-shield-timestamp.md) | No |  |
| `id` | [api-shield_schemas-uuid](api-shield-schemas-uuid.md) | No |  |
| `is_learned` | boolean | No | True if schema is Cloudflare-provided. |
| `name` | string | No | Schema file name. |

