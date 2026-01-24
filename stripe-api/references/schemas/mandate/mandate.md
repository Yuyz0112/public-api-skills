# mandate

A Mandate is a record of the permission that your customer gives you to debit their payment method.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `customer_acceptance` | [customer_acceptance](customer-acceptance.md) | Yes |  |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `multi_use` | [mandate_multi_use](mandate-multi-use.md) | No |  |
| `object` | enum: mandate | Yes | String representing the object's type. Objects of the same type share the same value. |
| `on_behalf_of` | string | No | The account (if any) that the mandate is intended for. |
| `payment_method` | any | Yes | ID of the payment method associated with this mandate. |
| `payment_method_details` | [mandate_payment_method_details](mandate-payment-method-details.md) | Yes |  |
| `single_use` | [mandate_single_use](mandate-single-use.md) | No |  |
| `status` | enum: active, inactive, pending | Yes | The mandate status indicates whether or not you can use it to initiate a payment. |
| `type` | enum: multi_use, single_use | Yes | The type of the mandate. |

