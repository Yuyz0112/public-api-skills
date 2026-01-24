# issuing.transaction

Any use of an [issued card](https://docs.stripe.com/issuing) that results in funds entering or leaving
your Stripe account, such as a completed purchase or refund, is represented by an Issuing
`Transaction` object.

Related guide: [Issued card transactions](https://docs.stripe.com/issuing/purchases/transactions)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The transaction amount, which will be reflected in your balance. This amount is in your currency and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `amount_details` | any | No | Detailed breakdown of amount components. These amounts are denominated in `currency` and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `authorization` | any | No | The `Authorization` object that led to this transaction. |
| `balance_transaction` | any | No | ID of the [balance transaction](https://docs.stripe.com/api/balance_transactions) associated with this transaction. |
| `card` | any | Yes | The card used to make this transaction. |
| `cardholder` | any | No | The cardholder to whom this transaction belongs. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `dispute` | any | No | If you've disputed the transaction, the ID of the dispute. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `merchant_amount` | integer | Yes | The amount that the merchant will receive, denominated in `merchant_currency` and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). It will be different from `amount` if the merchant is taking payment in a different currency. |
| `merchant_currency` | string (currency) | Yes | The currency with which the merchant is taking payment. |
| `merchant_data` | [issuing_authorization_merchant_data](issuing-authorization-merchant-data.md) | Yes |  |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `network_data` | any | No | Details about the transaction, such as processing dates, set by the card network. |
| `object` | enum: issuing.transaction | Yes | String representing the object's type. Objects of the same type share the same value. |
| `purchase_details` | any | No | Additional purchase information that is optionally provided by the merchant. |
| `token` | any | No | [Token](https://docs.stripe.com/api/issuing/tokens/object) object used for this transaction. If a network token was not used for this transaction, this field will be null. |
| `treasury` | any | No | [Treasury](https://docs.stripe.com/api/treasury) details related to this transaction if it was created on a [FinancialAccount](/docs/api/treasury/financial_accounts |
| `type` | enum: capture, refund | Yes | The nature of the transaction. |
| `wallet` | enum: apple_pay, google_pay, samsung_pay | No | The digital wallet used for this transaction. One of `apple_pay`, `google_pay`, or `samsung_pay`. |

