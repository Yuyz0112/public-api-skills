# treasury.credit_reversal

You can reverse some [ReceivedCredits](https://api.stripe.com#received_credits) depending on their network and source flow. Reversing a ReceivedCredit leads to the creation of a new object known as a CreditReversal.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount (in cents) transferred. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `financial_account` | string | Yes | The FinancialAccount to reverse funds from. |
| `hosted_regulatory_receipt_url` | string | No | A [hosted transaction receipt](https://docs.stripe.com/treasury/moving-money/regulatory-receipts) URL that is provided when money movement is considered regulated under Stripe's money transmission licenses. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `network` | enum: ach, stripe | Yes | The rails used to reverse the funds. |
| `object` | enum: treasury.credit_reversal | Yes | String representing the object's type. Objects of the same type share the same value. |
| `received_credit` | string | Yes | The ReceivedCredit being reversed. |
| `status` | enum: canceled, posted, processing | Yes | Status of the CreditReversal |
| `status_transitions` | [treasury_received_credits_resource_status_transitions](treasury-received-credits-resource-status-transitions.md) | Yes |  |
| `transaction` | any | No | The Transaction associated with this object. |

