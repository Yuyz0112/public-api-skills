# balance_transaction

Balance transactions represent funds moving through your Stripe account.
Stripe creates them for every type of transaction that enters or leaves your Stripe account balance.

Related guide: [Balance transaction types](https://docs.stripe.com/reports/balance-transaction-types)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Gross amount of this transaction (in cents (or local equivalent)). A positive value represents funds charged to another party, and a negative value represents funds sent to another party. |
| `available_on` | integer (unix-time) | Yes | The date that the transaction's net funds become available in the Stripe balance. |
| `balance_type` | enum: issuing, payments, refund_and_dispute_prefunding... | Yes | The balance that this transaction impacts. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `exchange_rate` | number | No | If applicable, this transaction uses an exchange rate. If money converts from currency A to currency B, then the `amount` in currency A, multipled by the `exchange_rate`, equals the `amount` in currency B. For example, if you charge a customer 10.00 EUR, the PaymentIntent's `amount` is `1000` and `currency` is `eur`. If this converts to 12.34 USD in your Stripe account, the BalanceTransaction's `amount` is `1234`, its `currency` is `usd`, and the `exchange_rate` is `1.234`. |
| `fee` | integer | Yes | Fees (in cents (or local equivalent)) paid for this transaction. Represented as a positive integer when assessed. |
| `fee_details` | fee[] | Yes | Detailed breakdown of fees (in cents (or local equivalent)) paid for this transaction. |
| `id` | string | Yes | Unique identifier for the object. |
| `net` | integer | Yes | Net impact to a Stripe balance (in cents (or local equivalent)). A positive value represents incrementing a Stripe balance, and a negative value decrementing a Stripe balance. You can calculate the net impact of a transaction on a balance by `amount` - `fee` |
| `object` | enum: balance_transaction | Yes | String representing the object's type. Objects of the same type share the same value. |
| `reporting_category` | string | Yes | Learn more about how [reporting categories](https://stripe.com/docs/reports/reporting-categories) can help you understand balance transactions from an accounting perspective. |
| `source` | any | No | This transaction relates to the Stripe object. |
| `status` | string | Yes | The transaction's net funds status in the Stripe balance, which are either `available` or `pending`. |
| `type` | enum: adjustment, advance, advance_funding... | Yes | Transaction type: `adjustment`, `advance`, `advance_funding`, `anticipation_repayment`, `application_fee`, `application_fee_refund`, `charge`, `climate_order_purchase`, `climate_order_refund`, `connect_collection_transfer`, `contribution`, `issuing_authorization_hold`, `issuing_authorization_release`, `issuing_dispute`, `issuing_transaction`, `obligation_outbound`, `obligation_reversal_inbound`, `payment`, `payment_failure_refund`, `payment_network_reserve_hold`, `payment_network_reserve_release`, `payment_refund`, `payment_reversal`, `payment_unreconciled`, `payout`, `payout_cancel`, `payout_failure`, `payout_minimum_balance_hold`, `payout_minimum_balance_release`, `refund`, `refund_failure`, `reserve_transaction`, `reserved_funds`, `reserve_hold`, `reserve_release`, `stripe_fee`, `stripe_fx_fee`, `stripe_balance_payment_debit`, `stripe_balance_payment_debit_reversal`, `tax_fee`, `topup`, `topup_reversal`, `transfer`, `transfer_cancel`, `transfer_failure`, or `transfer_refund`. Learn more about [balance transaction types and what they represent](https://stripe.com/docs/reports/balance-transaction-types). To classify transactions for accounting purposes, consider `reporting_category` instead. |

