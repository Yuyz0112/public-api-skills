# source

`Source` objects allow you to accept a variety of payment methods. They
represent a customer's payment instrument, and can be used with the Stripe API
just like a `Card` object: once chargeable, they can be charged, or can be
attached to customers.

Stripe doesn't recommend using the deprecated [Sources API](https://docs.stripe.com/api/sources).
We recommend that you adopt the [PaymentMethods API](https://docs.stripe.com/api/payment_methods).
This newer API provides access to our latest features and payment method types.

Related guides: [Sources API](https://docs.stripe.com/sources) and [Sources & Customers](https://docs.stripe.com/sources/customers).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ach_credit_transfer` | [source_type_ach_credit_transfer](source-type-ach-credit-transfer.md) | No |  |
| `ach_debit` | [source_type_ach_debit](source-type-ach-debit.md) | No |  |
| `acss_debit` | [source_type_acss_debit](source-type-acss-debit.md) | No |  |
| `alipay` | [source_type_alipay](source-type-alipay.md) | No |  |
| `allow_redisplay` | enum: always, limited, unspecified | No | This field indicates whether this payment method can be shown again to its customer in a checkout flow. Stripe products such as Checkout and Elements use this field to determine whether a payment method can be shown as a saved payment method in a checkout flow. The field defaults to “unspecified”. |
| `amount` | integer | No | A positive integer in the smallest currency unit (that is, 100 cents for $1.00, or 1 for ¥1, Japanese Yen being a zero-decimal currency) representing the total amount associated with the source. This is the amount for which the source will be chargeable once ready. Required for `single_use` sources. |
| `au_becs_debit` | [source_type_au_becs_debit](source-type-au-becs-debit.md) | No |  |
| `bancontact` | [source_type_bancontact](source-type-bancontact.md) | No |  |
| `card` | [source_type_card](source-type-card.md) | No |  |
| `card_present` | [source_type_card_present](source-type-card-present.md) | No |  |
| `client_secret` | string | Yes | The client secret of the source. Used for client-side retrieval using a publishable key. |
| `code_verification` | [source_code_verification_flow](source-code-verification-flow.md) | No |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | No | Three-letter [ISO code for the currency](https://stripe.com/docs/currencies) associated with the source. This is the currency for which the source will be chargeable once ready. Required for `single_use` sources. |
| `customer` | string | No | The ID of the customer to which this source is attached. This will not be present when the source has not been attached to a customer. |
| `eps` | [source_type_eps](source-type-eps.md) | No |  |
| `flow` | string | Yes | The authentication `flow` of the source. `flow` is one of `redirect`, `receiver`, `code_verification`, `none`. |
| `giropay` | [source_type_giropay](source-type-giropay.md) | No |  |
| `id` | string | Yes | Unique identifier for the object. |
| `ideal` | [source_type_ideal](source-type-ideal.md) | No |  |
| `klarna` | [source_type_klarna](source-type-klarna.md) | No |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `multibanco` | [source_type_multibanco](source-type-multibanco.md) | No |  |
| `object` | enum: source | Yes | String representing the object's type. Objects of the same type share the same value. |
| `owner` | any | No | Information about the owner of the payment instrument that may be used or required by particular source types. |
| `p24` | [source_type_p24](source-type-p24.md) | No |  |
| `receiver` | [source_receiver_flow](source-receiver-flow.md) | No |  |
| `redirect` | [source_redirect_flow](source-redirect-flow.md) | No |  |
| `sepa_debit` | [source_type_sepa_debit](source-type-sepa-debit.md) | No |  |
| `sofort` | [source_type_sofort](source-type-sofort.md) | No |  |
| `source_order` | [source_order](source-order.md) | No |  |
| `statement_descriptor` | string | No | Extra information about a source. This will appear on your customer's statement every time you charge the source. |
| `status` | string | Yes | The status of the source, one of `canceled`, `chargeable`, `consumed`, `failed`, or `pending`. Only `chargeable` sources can be used to create a charge. |
| `three_d_secure` | [source_type_three_d_secure](source-type-three-d-secure.md) | No |  |
| `type` | enum: ach_credit_transfer, ach_debit, acss_debit... | Yes | The `type` of the source. The `type` is a payment method, one of `ach_credit_transfer`, `ach_debit`, `alipay`, `bancontact`, `card`, `card_present`, `eps`, `giropay`, `ideal`, `multibanco`, `klarna`, `p24`, `sepa_debit`, `sofort`, `three_d_secure`, or `wechat`. An additional hash is included on the source with a name matching this value. It contains additional information specific to the [payment method](https://docs.stripe.com/sources) used. |
| `usage` | string | No | Either `reusable` or `single_use`. Whether this source should be reusable or not. Some source types may or may not be reusable by construction, while others may leave the option at creation. If an incompatible value is passed, an error will be returned. |
| `wechat` | [source_type_wechat](source-type-wechat.md) | No |  |

