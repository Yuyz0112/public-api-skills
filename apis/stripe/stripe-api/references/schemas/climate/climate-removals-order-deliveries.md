# climate_removals_order_deliveries

The delivery of a specified quantity of carbon for an order.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `delivered_at` | integer (unix-time) | Yes | Time at which the delivery occurred. Measured in seconds since the Unix epoch. |
| `location` | any | No | Specific location of this delivery. |
| `metric_tons` | string | Yes | Quantity of carbon removal supplied by this delivery. |
| `registry_url` | string | No | Once retired, a URL to the registry entry for the tons from this delivery. |
| `supplier` | [climate.supplier](climate-supplier.md) | Yes |  |

