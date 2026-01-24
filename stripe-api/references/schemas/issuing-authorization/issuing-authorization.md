# issuing.authorization

When an [issued card](https://docs.stripe.com/issuing) is used to make a purchase, an Issuing `Authorization`
object is created. [Authorizations](https://docs.stripe.com/issuing/purchases/authorizations) must be approved for the
purchase to be completed successfully.

Related guide: [Issued card authorizations](https://docs.stripe.com/issuing/purchases/authorizations)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The total amount that was authorized or rejected. This amount is in `currency` and in the [smallest currency unit](https://stripe.com/docs/currencies#zero-decimal). `amount` should be the same as `merchant_amount`, unless `currency` and `merchant_currency` are different. |
| `amount_details` | any | No | Detailed breakdown of amount components. These amounts are denominated in `currency` and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `approved` | boolean | Yes | Whether the authorization has been approved. |
| `authorization_method` | enum: chip, contactless, keyed_in... | Yes | How the card details were provided. |
| `balance_transactions` | balance_transaction[] | Yes | List of balance transactions associated with this authorization. |
| `card` | [issuing.card](issuing-card.md) | Yes |  |
| `cardholder` | any | No | The cardholder to whom this authorization belongs. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | The currency of the cardholder. This currency can be different from the currency presented at authorization and the `merchant_currency` field on this authorization. Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `fleet` | any | No | Fleet-specific information for authorizations using Fleet cards. |
| `fraud_challenges` | issuing_authorization_fraud_challenge[] | No | Fraud challenges sent to the cardholder, if this authorization was declined for fraud risk reasons. |
| `fuel` | any | No | Information about fuel that was purchased with this transaction. Typically this information is received from the merchant after the authorization has been approved and the fuel dispensed. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `merchant_amount` | integer | Yes | The total amount that was authorized or rejected. This amount is in the `merchant_currency` and in the [smallest currency unit](https://stripe.com/docs/currencies#zero-decimal). `merchant_amount` should be the same as `amount`, unless `merchant_currency` and `currency` are different. |
| `merchant_currency` | string (currency) | Yes | The local currency that was presented to the cardholder for the authorization. This currency can be different from the cardholder currency and the `currency` field on this authorization. Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `merchant_data` | [issuing_authorization_merchant_data](issuing-authorization-merchant-data.md) | Yes |  |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `network_data` | any | No | Details about the authorization, such as identifiers, set by the card network. |
| `object` | enum: issuing.authorization | Yes | String representing the object's type. Objects of the same type share the same value. |
| `pending_request` | any | No | The pending authorization request. This field will only be non-null during an `issuing_authorization.request` webhook. |
| `request_history` | issuing_authorization_request[] | Yes | History of every time a `pending_request` authorization was approved/declined, either by you directly or by Stripe (e.g. based on your spending_controls). If the merchant changes the authorization by performing an incremental authorization, you can look at this field to see the previous requests for the authorization. This field can be helpful in determining why a given authorization was approved/declined. |
| `status` | enum: closed, expired, pending... | Yes | The current status of the authorization in its lifecycle. |
| `token` | any | No | [Token](https://docs.stripe.com/api/issuing/tokens/object) object used for this authorization. If a network token was not used for this authorization, this field will be null. |
| `transactions` | issuing.transaction[] | Yes | List of [transactions](https://docs.stripe.com/api/issuing/transactions) associated with this authorization. |
| `treasury` | any | No | [Treasury](https://docs.stripe.com/api/treasury) details related to this authorization if it was created on a [FinancialAccount](https://docs.stripe.com/api/treasury/financial_accounts). |
| `verification_data` | [issuing_authorization_verification_data](issuing-authorization-verification-data.md) | Yes |  |
| `verified_by_fraud_challenge` | boolean | No | Whether the authorization bypassed fraud risk checks because the cardholder has previously completed a fraud challenge on a similar high-risk authorization from the same merchant. |
| `wallet` | string | No | The digital wallet used for this transaction. One of `apple_pay`, `google_pay`, or `samsung_pay`. Will populate as `null` when no digital wallet was utilized. |

