# api-shield_per_operation_setting

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mitigation_action` | enum: log, block, none | Yes | When set, this applies a mitigation action to this operation which supersedes a global schema validation setting just for this operation

  - `"log"` - log request when request does not conform to schema for this operation
  - `"block"` - deny access to the site when request does not conform to schema for this operation
  - `"none"` - will skip mitigation for this operation
 |
| `operation_id` | [api-shield_schemas-uuid](api-shield-schemas-uuid.md) | Yes |  |

