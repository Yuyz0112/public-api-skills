# treasury_transactions_resource_flow_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `credit_reversal` | [treasury.credit_reversal](treasury-credit-reversal.md) | No |  |
| `debit_reversal` | [treasury.debit_reversal](treasury-debit-reversal.md) | No |  |
| `inbound_transfer` | [treasury.inbound_transfer](treasury-inbound-transfer.md) | No |  |
| `issuing_authorization` | [issuing.authorization](issuing-authorization.md) | No |  |
| `outbound_payment` | [treasury.outbound_payment](treasury-outbound-payment.md) | No |  |
| `outbound_transfer` | [treasury.outbound_transfer](treasury-outbound-transfer.md) | No |  |
| `received_credit` | [treasury.received_credit](treasury-received-credit.md) | No |  |
| `received_debit` | [treasury.received_debit](treasury-received-debit.md) | No |  |
| `type` | enum: credit_reversal, debit_reversal, inbound_transfer... | Yes | Type of the flow that created the Transaction. Set to the same value as `flow_type`. |

