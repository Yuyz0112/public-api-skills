# capability

This is an object representing a capability for a Stripe account.

Related guide: [Account capabilities](https://docs.stripe.com/connect/account-capabilities)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | any | Yes | The account for which the capability enables functionality. |
| `future_requirements` | [account_capability_future_requirements](account-capability-future-requirements.md) | No |  |
| `id` | string | Yes | The identifier for the capability. |
| `object` | enum: capability | Yes | String representing the object's type. Objects of the same type share the same value. |
| `requested` | boolean | Yes | Whether the capability has been requested. |
| `requested_at` | integer (unix-time) | No | Time at which the capability was requested. Measured in seconds since the Unix epoch. |
| `requirements` | [account_capability_requirements](account-capability-requirements.md) | No |  |
| `status` | enum: active, inactive, pending... | Yes | The status of the capability. |

