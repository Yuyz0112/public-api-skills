# api-shield_old_validation_default_mitigation_action_patch

The default mitigation action used when there is no mitigation action defined on the operation
Mitigation actions are as follows:

  * `log` - log request when request does not conform to schema
  * `block` - deny access to the site when request does not conform to schema

A special value of of `none` will skip running schema validation entirely for the request when there is no mitigation action defined on the operation

`null` will have no effect.


**Type:** enum

## Values

- `none`
- `log`
- `block`
- `null`
