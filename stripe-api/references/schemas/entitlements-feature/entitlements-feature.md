# entitlements.feature

A feature represents a monetizable ability or functionality in your system.
Features can be assigned to products, and when those products are purchased, Stripe will create an entitlement to the feature for the purchasing customer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes | Inactive features cannot be attached to new products and will not be returned from the features list endpoint. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `lookup_key` | string | Yes | A unique key you provide as your own system identifier. This may be up to 80 characters. |
| `metadata` | object | Yes | Set of key-value pairs that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name` | string | Yes | The feature's name, for your own purpose, not meant to be displayable to the customer. |
| `object` | enum: entitlements.feature | Yes | String representing the object's type. Objects of the same type share the same value. |

