# zero-trust-gateway_expiration

Defines the expiration time stamp and default duration of a DNS policy. Takes precedence over the policy's `schedule` configuration, if any. This  does not apply to HTTP or network policies. Settable only for `dns` rules.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `duration` | integer | No | Defines the default duration a policy active in minutes. Must set in order to use the `reset_expiration` endpoint on this rule. |
| `expired` | boolean | No | Indicates whether the policy is expired. |
| `expires_at` | any | Yes |  |

