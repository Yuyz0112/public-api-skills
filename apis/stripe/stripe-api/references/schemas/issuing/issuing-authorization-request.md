# issuing_authorization_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The `pending_request.amount` at the time of the request, presented in your card's currency and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). Stripe held this amount from your account to fund the authorization if the request was approved. |
| `amount_details` | any | No | Detailed breakdown of amount components. These amounts are denominated in `currency` and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `approved` | boolean | Yes | Whether this request was approved. |
| `authorization_code` | string | No | A code created by Stripe which is shared with the merchant to validate the authorization. This field will be populated if the authorization message was approved. The code typically starts with the letter "S", followed by a six-digit number. For example, "S498162". Please note that the code is not guaranteed to be unique across authorizations. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `merchant_amount` | integer | Yes | The `pending_request.merchant_amount` at the time of the request, presented in the `merchant_currency` and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `merchant_currency` | string | Yes | The currency that was collected by the merchant and presented to the cardholder for the authorization. Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `network_risk_score` | integer | No | The card network's estimate of the likelihood that an authorization is fraudulent. Takes on values between 1 and 99. |
| `reason` | enum: account_disabled, card_active, card_canceled... | Yes | When an authorization is approved or declined by you or by Stripe, this field provides additional detail on the reason for the outcome. |
| `reason_message` | string | No | If the `request_history.reason` is `webhook_error` because the direct webhook response is invalid (for example, parsing errors or missing parameters), we surface a more detailed error message via this field. |
| `requested_at` | integer (unix-time) | No | Time when the card network received an authorization request from the acquirer in UTC. Referred to by networks as transmission time. |

