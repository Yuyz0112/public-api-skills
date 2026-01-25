# climate.order

Orders represent your intent to purchase a particular Climate product. When you create an order, the
payment is deducted from your merchant balance.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_fees` | integer | Yes | Total amount of [Frontier](https://frontierclimate.com/)'s service fees in the currency's smallest unit. |
| `amount_subtotal` | integer | Yes | Total amount of the carbon removal in the currency's smallest unit. |
| `amount_total` | integer | Yes | Total amount of the order including fees in the currency's smallest unit. |
| `beneficiary` | [climate_removals_beneficiary](climate-removals-beneficiary.md) | No |  |
| `canceled_at` | integer (unix-time) | No | Time at which the order was canceled. Measured in seconds since the Unix epoch. |
| `cancellation_reason` | enum: expired, product_unavailable, requested | No | Reason for the cancellation of this order. |
| `certificate` | string | No | For delivered orders, a URL to a delivery certificate for the order. |
| `confirmed_at` | integer (unix-time) | No | Time at which the order was confirmed. Measured in seconds since the Unix epoch. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase, representing the currency for this order. |
| `delayed_at` | integer (unix-time) | No | Time at which the order's expected_delivery_year was delayed. Measured in seconds since the Unix epoch. |
| `delivered_at` | integer (unix-time) | No | Time at which the order was delivered. Measured in seconds since the Unix epoch. |
| `delivery_details` | climate_removals_order_deliveries[] | Yes | Details about the delivery of carbon removal for this order. |
| `expected_delivery_year` | integer | Yes | The year this order is expected to be delivered. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `metric_tons` | string (decimal) | Yes | Quantity of carbon removal that is included in this order. |
| `object` | enum: climate.order | Yes | String representing the object's type. Objects of the same type share the same value. |
| `product` | any | Yes | Unique ID for the Climate `Product` this order is purchasing. |
| `product_substituted_at` | integer (unix-time) | No | Time at which the order's product was substituted for a different product. Measured in seconds since the Unix epoch. |
| `status` | enum: awaiting_funds, canceled, confirmed... | Yes | The current status of this order. |

