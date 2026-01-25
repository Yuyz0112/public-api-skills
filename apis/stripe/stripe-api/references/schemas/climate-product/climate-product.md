# climate.product

A Climate product represents a type of carbon removal unit available for reservation.
You can retrieve it to see the current price and availability.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `current_prices_per_metric_ton` | object | Yes | Current prices for a metric ton of carbon removal in a currency's smallest unit. |
| `delivery_year` | integer | No | The year in which the carbon removal is expected to be delivered. |
| `id` | string | Yes | Unique identifier for the object. For convenience, Climate product IDs are human-readable strings
that start with `climsku_`. See [carbon removal inventory](https://stripe.com/docs/climate/orders/carbon-removal-inventory)
for a list of available carbon removal products. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metric_tons_available` | string (decimal) | Yes | The quantity of metric tons available for reservation. |
| `name` | string | Yes | The Climate product's name. |
| `object` | enum: climate.product | Yes | String representing the object's type. Objects of the same type share the same value. |
| `suppliers` | climate.supplier[] | Yes | The carbon removal suppliers that fulfill orders for this Climate product. |

