# issuing.dispute

As a [card issuer](https://docs.stripe.com/issuing), you can dispute transactions that the cardholder does not recognize, suspects to be fraudulent, or has other issues with.

Related guide: [Issuing disputes](https://docs.stripe.com/issuing/purchases/disputes)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Disputed amount in the card's currency and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). Usually the amount of the `transaction`, but can differ (usually because of currency fluctuation). |
| `balance_transactions` | balance_transaction[] | No | List of balance transactions associated with the dispute. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | The currency the `transaction` was made in. |
| `evidence` | [issuing_dispute_evidence](issuing-dispute-evidence.md) | Yes |  |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `loss_reason` | enum: cardholder_authentication_issuer_liability, eci5_token_transaction_with_tavv, excess_disputes_in_timeframe... | No | The enum that describes the dispute loss outcome. If the dispute is not lost, this field will be absent. New enum values may be added in the future, so be sure to handle unknown values. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: issuing.dispute | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: expired, lost, submitted... | Yes | Current status of the dispute. |
| `transaction` | any | Yes | The transaction being disputed. |
| `treasury` | any | No | [Treasury](https://docs.stripe.com/api/treasury) details related to this dispute if it was created on a [FinancialAccount](/docs/api/treasury/financial_accounts |

