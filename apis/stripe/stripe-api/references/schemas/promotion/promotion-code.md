# promotion_code

A Promotion Code represents a customer-redeemable code for an underlying promotion.
You can create multiple codes for a single promotion.

If you enable promotion codes in your [customer portal configuration](https://docs.stripe.com/customer-management/configure-portal), then customers can redeem a code themselves when updating a subscription in the portal.
Customers can also view the currently active promotion codes and coupons on each of their subscriptions in the portal.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes | Whether the promotion code is currently active. A promotion code is only active if the coupon is also valid. |
| `code` | string | Yes | The customer-facing code. Regardless of case, this code must be unique across all active promotion codes for each customer. Valid characters are lower case letters (a-z), upper case letters (A-Z), and digits (0-9). |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `customer` | any | No | The customer who can use this promotion code. |
| `customer_account` | string | No | The account representing the customer who can use this promotion code. |
| `expires_at` | integer (unix-time) | No | Date at which the promotion code can no longer be redeemed. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `max_redemptions` | integer | No | Maximum number of times this promotion code can be redeemed. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: promotion_code | Yes | String representing the object's type. Objects of the same type share the same value. |
| `promotion` | [promotion_codes_resource_promotion](promotion-codes-resource-promotion.md) | Yes |  |
| `restrictions` | [promotion_codes_resource_restrictions](promotion-codes-resource-restrictions.md) | Yes |  |
| `times_redeemed` | integer | Yes | Number of times this promotion code has been used. |

