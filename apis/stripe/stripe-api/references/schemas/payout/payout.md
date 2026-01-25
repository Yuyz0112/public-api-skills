# payout

A `Payout` object is created when you receive funds from Stripe, or when you
initiate a payout to either a bank account or debit card of a [connected
Stripe account](/docs/connect/bank-debit-card-payouts). You can retrieve individual payouts,
and list all payouts. Payouts are made on [varying
schedules](/docs/connect/manage-payout-schedule), depending on your country and
industry.

Related guide: [Receiving payouts](https://docs.stripe.com/payouts)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The amount (in cents (or local equivalent)) that transfers to your bank account or debit card. |
| `application_fee` | any | No | The application fee (if any) for the payout. [See the Connect documentation](https://docs.stripe.com/connect/instant-payouts#monetization-and-fees) for details. |
| `application_fee_amount` | integer | No | The amount of the application fee (if any) requested for the payout. [See the Connect documentation](https://docs.stripe.com/connect/instant-payouts#monetization-and-fees) for details. |
| `arrival_date` | integer (unix-time) | Yes | Date that you can expect the payout to arrive in the bank. This factors in delays to account for weekends or bank holidays. |
| `automatic` | boolean | Yes | Returns `true` if the payout is created by an [automated payout schedule](https://docs.stripe.com/payouts#payout-schedule) and `false` if it's [requested manually](https://stripe.com/docs/payouts#manual-payouts). |
| `balance_transaction` | any | No | ID of the balance transaction that describes the impact of this payout on your account balance. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `destination` | any | No | ID of the bank account or card the payout is sent to. |
| `failure_balance_transaction` | any | No | If the payout fails or cancels, this is the ID of the balance transaction that reverses the initial balance transaction and returns the funds from the failed payout back in your balance. |
| `failure_code` | string | No | Error code that provides a reason for a payout failure, if available. View our [list of failure codes](https://docs.stripe.com/api#payout_failures). |
| `failure_message` | string | No | Message that provides the reason for a payout failure, if available. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `method` | string | Yes | The method used to send this payout, which can be `standard` or `instant`. `instant` is supported for payouts to debit cards and bank accounts in certain countries. Learn more about [bank support for Instant Payouts](https://stripe.com/docs/payouts/instant-payouts-banks). |
| `object` | enum: payout | Yes | String representing the object's type. Objects of the same type share the same value. |
| `original_payout` | any | No | If the payout reverses another, this is the ID of the original payout. |
| `payout_method` | string | No | ID of the v2 FinancialAccount the funds are sent to. |
| `reconciliation_status` | enum: completed, in_progress, not_applicable | Yes | If `completed`, you can use the [Balance Transactions API](https://docs.stripe.com/api/balance_transactions/list#balance_transaction_list-payout) to list all balance transactions that are paid out in this payout. |
| `reversed_by` | any | No | If the payout reverses, this is the ID of the payout that reverses this payout. |
| `source_type` | string | Yes | The source balance this payout came from, which can be one of the following: `card`, `fpx`, or `bank_account`. |
| `statement_descriptor` | string | No | Extra information about a payout that displays on the user's bank statement. |
| `status` | string | Yes | Current status of the payout: `paid`, `pending`, `in_transit`, `canceled` or `failed`. A payout is `pending` until it's submitted to the bank, when it becomes `in_transit`. The status changes to `paid` if the transaction succeeds, or to `failed` or `canceled` (within 5 business days). Some payouts that fail might initially show as `paid`, then change to `failed`. |
| `trace_id` | any | No | A value that generates from the beneficiary's bank that allows users to track payouts with their bank. Banks might call this a "reference number" or something similar. |
| `type` | enum: bank_account, card | Yes | Can be `bank_account` or `card`. |

