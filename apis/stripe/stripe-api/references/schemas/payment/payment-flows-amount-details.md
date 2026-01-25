# payment_flows_amount_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `discount_amount` | integer | No | The total discount applied on the transaction represented in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). An integer greater than 0.

This field is mutually exclusive with the `amount_details[line_items][#][discount_amount]` field. |
| `error` | [payment_flows_amount_details_resource_error](payment-flows-amount-details-resource-error.md) | No |  |
| `line_items` | object | No | A list of line items, each containing information about a product in the PaymentIntent. There is a maximum of 200 line items. |
| `shipping` | [payment_flows_amount_details_resource_shipping](payment-flows-amount-details-resource-shipping.md) | No |  |
| `tax` | [payment_flows_amount_details_resource_tax](payment-flows-amount-details-resource-tax.md) | No |  |
| `tip` | [payment_flows_amount_details_client_resource_tip](payment-flows-amount-details-client-resource-tip.md) | No |  |

## Nested Fields

### `line_items`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | payment_intent_amount_details_line_item[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

