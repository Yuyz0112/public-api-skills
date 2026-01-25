# api-shield_global_settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `validation_default_mitigation_action` | enum: none, log, block | Yes | The default mitigation action used

Mitigation actions are as follows:

  - `log` - log request when request does not conform to schema
  - `block` - deny access to the site when request does not conform to schema
  - `none` - skip running schema validation
 |
| `validation_override_mitigation_action` | enum: none | No | When not null, this overrides global both zone level and operation level mitigation actions. This can serve as a quick way to disable schema validation for the whole zone.

  - `"none"` will skip running schema validation entirely for the request
 |

