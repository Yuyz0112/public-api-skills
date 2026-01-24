# payment_method_us_bank_account_blocked

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `network_code` | enum: R02, R03, R04... | No | The ACH network code that resulted in this block. |
| `reason` | enum: bank_account_closed, bank_account_frozen, bank_account_invalid_details... | No | The reason why this PaymentMethod's fingerprint has been blocked |

