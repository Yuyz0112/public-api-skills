# payment_links_resource_payment_intent_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `capture_method` | enum: automatic, automatic_async, manual | No | Indicates when the funds will be captured from the customer's account. |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that will set metadata on [Payment Intents](https://docs.stripe.com/api/payment_intents) generated from this payment link. |
| `setup_future_usage` | enum: off_session, on_session | No | Indicates that you intend to make future payments with the payment method collected during checkout. |
| `statement_descriptor` | string | No | For a non-card payment, information about the charge that appears on the customer's statement when this payment succeeds in creating a charge. |
| `statement_descriptor_suffix` | string | No | For a card payment, information about the charge that appears on the customer's statement when this payment succeeds in creating a charge. Concatenated with the account's statement descriptor prefix to form the complete statement descriptor. |
| `transfer_group` | string | No | A string that identifies the resulting payment as part of a group. See the PaymentIntents [use case for connected accounts](https://docs.stripe.com/connect/separate-charges-and-transfers) for details. |

