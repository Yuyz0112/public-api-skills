# issuing.physical_bundle

A Physical Bundle represents the bundle of physical items - card stock, carrier letter, and envelope - that is shipped to a cardholder when you create a physical card.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `features` | [issuing_physical_bundle_features](issuing-physical-bundle-features.md) | Yes |  |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `name` | string | Yes | Friendly display name. |
| `object` | enum: issuing.physical_bundle | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: active, inactive, review | Yes | Whether this physical bundle can be used to create cards. |
| `type` | enum: custom, standard | Yes | Whether this physical bundle is a standard Stripe offering or custom-made for you. |

