# issuing.settlement

When a non-stripe BIN is used, any use of an [issued card](https://docs.stripe.com/issuing) must be settled directly with the card network. The net amount owed is represented by an Issuing `Settlement` object.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bin` | string | Yes | The Bank Identification Number reflecting this settlement record. |
| `clearing_date` | integer (unix-time) | Yes | The date that the transactions are cleared and posted to user's accounts. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `id` | string | Yes | Unique identifier for the object. |
| `interchange_fees_amount` | integer | Yes | The total interchange received as reimbursement for the transactions. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `net_total_amount` | integer | Yes | The total net amount required to settle with the network. |
| `network` | enum: maestro, visa | Yes | The card network for this settlement report. One of ["visa", "maestro"] |
| `network_fees_amount` | integer | Yes | The total amount of fees owed to the network. |
| `network_settlement_identifier` | string | Yes | The Settlement Identification Number assigned by the network. |
| `object` | enum: issuing.settlement | Yes | String representing the object's type. Objects of the same type share the same value. |
| `settlement_service` | string | Yes | One of `international` or `uk_national_net`. |
| `status` | enum: complete, pending | Yes | The current processing status of this settlement. |
| `transaction_amount` | integer | Yes | The total transaction amount reflected in this settlement. |
| `transaction_count` | integer | Yes | The total number of transactions reflected in this settlement. |

