# payment_record

A Payment Record is a resource that allows you to represent payments that occur on- or off-Stripe.
For example, you can create a Payment Record to model a payment made on a different payment processor,
in order to mark an Invoice as paid and a Subscription as active. Payment Records consist of one or
more Payment Attempt Records, which represent individual attempts made on a payment network.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | [payments_primitives_payment_records_resource_amount](payments-primitives-payment-records-resource-amount.md) | Yes |  |
| `amount_authorized` | [payments_primitives_payment_records_resource_amount](payments-primitives-payment-records-resource-amount.md) | Yes |  |
| `amount_canceled` | [payments_primitives_payment_records_resource_amount](payments-primitives-payment-records-resource-amount.md) | Yes |  |
| `amount_failed` | [payments_primitives_payment_records_resource_amount](payments-primitives-payment-records-resource-amount.md) | Yes |  |
| `amount_guaranteed` | [payments_primitives_payment_records_resource_amount](payments-primitives-payment-records-resource-amount.md) | Yes |  |
| `amount_refunded` | [payments_primitives_payment_records_resource_amount](payments-primitives-payment-records-resource-amount.md) | Yes |  |
| `amount_requested` | [payments_primitives_payment_records_resource_amount](payments-primitives-payment-records-resource-amount.md) | Yes |  |
| `application` | string | No | ID of the Connect application that created the PaymentRecord. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `customer_details` | any | No | Customer information for this payment. |
| `customer_presence` | enum: off_session, on_session | No | Indicates whether the customer was present in your checkout flow during this payment. |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `id` | string | Yes | Unique identifier for the object. |
| `latest_payment_attempt_record` | string | No | ID of the latest Payment Attempt Record attached to this Payment Record. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: payment_record | Yes | String representing the object's type. Objects of the same type share the same value. |
| `payment_method_details` | any | No | Information about the Payment Method debited for this payment. |
| `processor_details` | [payments_primitives_payment_records_resource_processor_details](payments-primitives-payment-records-resource-processor-details.md) | Yes |  |
| `reported_by` | enum: self, stripe | Yes | Indicates who reported the payment. |
| `shipping_details` | any | No | Shipping information for this payment. |

