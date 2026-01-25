# payment_flows_private_payment_methods_paypal_amount_details_line_item_payment_method_options

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `category` | enum: digital_goods, donation, physical_goods | No | Type of the line item. |
| `description` | string | No | Description of the line item. |
| `sold_by` | string | No | The Stripe account ID of the connected account that sells the item. This is only needed when using [Separate Charges and Transfers](https://docs.stripe.com/connect/separate-charges-and-transfers). |

