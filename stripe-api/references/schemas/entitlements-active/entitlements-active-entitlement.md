# entitlements.active_entitlement

An active entitlement describes access to a feature for a customer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `feature` | any | Yes | The [Feature](https://docs.stripe.com/api/entitlements/feature) that the customer is entitled to. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `lookup_key` | string | Yes | A unique key you provide as your own system identifier. This may be up to 80 characters. |
| `object` | enum: entitlements.active_entitlement | Yes | String representing the object's type. Objects of the same type share the same value. |

