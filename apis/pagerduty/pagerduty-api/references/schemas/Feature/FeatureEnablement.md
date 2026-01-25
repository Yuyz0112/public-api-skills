# FeatureEnablement

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `feature` | string | No | The name of the product addon whose set of features will be enabled or disabled. |
| `enabled` | boolean | Yes | A boolean value indicating whether the specified product addon is enabled or disabled. |
| `updated_at` | string (date-time) | No | The time the feature enablement was last updated. |
| `warnings` | object[] | No | An array of warnings related to this feature enablement. Only present if warning conditions are met. |

## Nested Fields

### `warnings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No | The warning message. |

