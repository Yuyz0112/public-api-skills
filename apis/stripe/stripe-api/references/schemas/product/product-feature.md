# product_feature

A product_feature represents an attachment between a feature and a product.
When a product is purchased that has a feature attached, Stripe will create an entitlement to the feature for the purchasing customer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `entitlement_feature` | [entitlements.feature](entitlements-feature.md) | Yes |  |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: product_feature | Yes | String representing the object's type. Objects of the same type share the same value. |

