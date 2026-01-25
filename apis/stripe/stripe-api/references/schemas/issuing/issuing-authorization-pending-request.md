# issuing_authorization_pending_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The additional amount Stripe will hold if the authorization is approved, in the card's [currency](https://docs.stripe.com/api#issuing_authorization_object-pending-request-currency) and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `amount_details` | any | No | Detailed breakdown of amount components. These amounts are denominated in `currency` and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `is_amount_controllable` | boolean | Yes | If set `true`, you may provide [amount](https://docs.stripe.com/api/issuing/authorizations/approve#approve_issuing_authorization-amount) to control how much to hold for the authorization. |
| `merchant_amount` | integer | Yes | The amount the merchant is requesting to be authorized in the `merchant_currency`. The amount is in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `merchant_currency` | string (currency) | Yes | The local currency the merchant is requesting to authorize. |
| `network_risk_score` | integer | No | The card network's estimate of the likelihood that an authorization is fraudulent. Takes on values between 1 and 99. |

