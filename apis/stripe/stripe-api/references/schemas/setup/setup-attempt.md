# setup_attempt

A SetupAttempt describes one attempted confirmation of a SetupIntent,
whether that confirmation is successful or unsuccessful. You can use
SetupAttempts to inspect details of a specific attempt at setting up a
payment method using a SetupIntent.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `application` | any | No | The value of [application](https://docs.stripe.com/api/setup_intents/object#setup_intent_object-application) on the SetupIntent at the time of this confirmation. |
| `attach_to_self` | boolean | No | If present, the SetupIntent's payment method will be attached to the in-context Stripe Account.

It can only be used for this Stripe Account’s own money movement flows like InboundTransfer and OutboundTransfers. It cannot be set to true when setting up a PaymentMethod for a Customer, and defaults to false when attaching a PaymentMethod to a Customer. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `customer` | any | No | The value of [customer](https://docs.stripe.com/api/setup_intents/object#setup_intent_object-customer) on the SetupIntent at the time of this confirmation. |
| `customer_account` | string | No | The value of [customer_account](https://docs.stripe.com/api/setup_intents/object#setup_intent_object-customer_account) on the SetupIntent at the time of this confirmation. |
| `flow_directions` | string[] | No | Indicates the directions of money movement for which this payment method is intended to be used.

Include `inbound` if you intend to use the payment method as the origin to pull funds from. Include `outbound` if you intend to use the payment method as the destination to send funds to. You can include both if you intend to use the payment method for both purposes. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: setup_attempt | Yes | String representing the object's type. Objects of the same type share the same value. |
| `on_behalf_of` | any | No | The value of [on_behalf_of](https://docs.stripe.com/api/setup_intents/object#setup_intent_object-on_behalf_of) on the SetupIntent at the time of this confirmation. |
| `payment_method` | any | Yes | ID of the payment method used with this SetupAttempt. |
| `payment_method_details` | [setup_attempt_payment_method_details](setup-attempt-payment-method-details.md) | Yes |  |
| `setup_error` | any | No | The error encountered during this attempt to confirm the SetupIntent, if any. |
| `setup_intent` | any | Yes | ID of the SetupIntent that this attempt belongs to. |
| `status` | string | Yes | Status of this SetupAttempt, one of `requires_confirmation`, `requires_action`, `processing`, `succeeded`, `failed`, or `abandoned`. |
| `usage` | string | Yes | The value of [usage](https://docs.stripe.com/api/setup_intents/object#setup_intent_object-usage) on the SetupIntent at the time of this confirmation, one of `off_session` or `on_session`. |

