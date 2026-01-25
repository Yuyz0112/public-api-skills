# api-shield_global_setting_change_base

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `validation_default_mitigation_action` | enum: none, log, block | No | The default mitigation action used
Mitigation actions are as follows:

  - `"log"` - log request when request does not conform to schema
  - `"block"` - deny access to the site when request does not conform to schema
  - `"none"` - skip running schema validation
 |
| `validation_override_mitigation_action` | enum: none,  | No | When set, this overrides both zone level and operation level mitigation actions.

  - `"none"` - skip running schema validation entirely for the request
  - `null` - clears any existing override
 |

