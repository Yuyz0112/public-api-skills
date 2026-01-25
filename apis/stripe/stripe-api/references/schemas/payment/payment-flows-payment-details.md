# payment_flows_payment_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `customer_reference` | string | No | A unique value to identify the customer. This field is available only for card payments.

This field is truncated to 25 alphanumeric characters, excluding spaces, before being sent to card networks. |
| `order_reference` | string | No | A unique value assigned by the business to identify the transaction. Required for L2 and L3 rates.

Required when the Payment Method Types array contains `card`, including when [automatic_payment_methods.enabled](/api/payment_intents/create#create_payment_intent-automatic_payment_methods-enabled) is set to `true`.

For Cards, this field is truncated to 25 alphanumeric characters, excluding spaces, before being sent to card networks. For Klarna, this field is truncated to 255 characters and is visible to customers when they view the order in the Klarna app. |

