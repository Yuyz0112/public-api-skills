# treasury_outbound_payments_resource_returned_status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | enum: account_closed, account_frozen, bank_account_restricted... | Yes | Reason for the return. |
| `transaction` | any | Yes | The Transaction associated with this object. |

