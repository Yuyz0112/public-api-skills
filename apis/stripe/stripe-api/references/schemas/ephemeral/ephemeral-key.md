# ephemeral_key

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `expires` | integer (unix-time) | Yes | Time at which the key will expire. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: ephemeral_key | Yes | String representing the object's type. Objects of the same type share the same value. |
| `secret` | string | No | The key's secret. You can use this value to make authorized requests to the Stripe API. |

