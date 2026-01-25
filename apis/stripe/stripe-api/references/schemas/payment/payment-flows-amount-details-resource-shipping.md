# payment_flows_amount_details_resource_shipping

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | No | If a physical good is being shipped, the cost of shipping represented in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). An integer greater than or equal to 0. |
| `from_postal_code` | string | No | If a physical good is being shipped, the postal code of where it is being shipped from. At most 10 alphanumeric characters long, hyphens are allowed. |
| `to_postal_code` | string | No | If a physical good is being shipped, the postal code of where it is being shipped to. At most 10 alphanumeric characters long, hyphens are allowed. |

