# mandate_bacs_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `network_status` | enum: accepted, pending, refused... | Yes | The status of the mandate on the Bacs network. Can be one of `pending`, `revoked`, `refused`, or `accepted`. |
| `reference` | string | Yes | The unique reference identifying the mandate on the Bacs network. |
| `revocation_reason` | enum: account_closed, bank_account_restricted, bank_ownership_changed... | No | When the mandate is revoked on the Bacs network this field displays the reason for the revocation. |
| `url` | string | Yes | The URL that will contain the mandate that the customer has signed. |

