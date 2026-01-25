# api-shield_old_validation_override_mitigation_action_patch

When set, this overrides both zone level and operation level mitigation actions.

  - `none` will skip running schema validation entirely for the request

To clear any override, use the special value `disable_override`

`null` will have no effect.


**Type:** enum

## Values

- `none`
- `disable_override`
- `null`
