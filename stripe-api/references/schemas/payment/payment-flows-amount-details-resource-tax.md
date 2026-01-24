# payment_flows_amount_details_resource_tax

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_tax_amount` | integer | No | The total amount of tax on the transaction represented in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). Required for L2 rates. An integer greater than or equal to 0.

This field is mutually exclusive with the `amount_details[line_items][#][tax][total_tax_amount]` field. |

