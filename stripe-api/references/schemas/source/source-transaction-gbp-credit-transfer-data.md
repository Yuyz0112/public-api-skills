# source_transaction_gbp_credit_transfer_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fingerprint` | string | No | Bank account fingerprint associated with the Stripe owned bank account receiving the transfer. |
| `funding_method` | string | No | The credit transfer rails the sender used to push this transfer. The possible rails are: Faster Payments, BACS, CHAPS, and wire transfers. Currently only Faster Payments is supported. |
| `last4` | string | No | Last 4 digits of sender account number associated with the transfer. |
| `reference` | string | No | Sender entered arbitrary information about the transfer. |
| `sender_account_number` | string | No | Sender account number associated with the transfer. |
| `sender_name` | string | No | Sender name associated with the transfer. |
| `sender_sort_code` | string | No | Sender sort code associated with the transfer. |

