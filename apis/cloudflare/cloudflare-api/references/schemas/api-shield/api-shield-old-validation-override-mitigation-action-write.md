# api-shield_old_validation_override_mitigation_action_write

When set, this overrides both zone level and operation level mitigation actions.

  - `none` will skip running schema validation entirely for the request
  - `null` indicates that no override is in place

To clear any override, use the special value `disable_override` or `null`


**Type:** enum

## Values

- `none`
- `disable_override`
- `null`
