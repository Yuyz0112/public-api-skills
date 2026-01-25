# api-shield_per_operation_setting_change_base

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mitigation_action` | enum: log, block, none... | No | When set, this applies a mitigation action to this operation

  - `"log"` - log request when request does not conform to schema for this operation
  - `"block"` - deny access to the site when request does not conform to schema for this operation
  - `"none"` - will skip mitigation for this operation
  - `null` - clears any mitigation action
 |

