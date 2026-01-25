# treasury_received_credits_resource_source_flows_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `credit_reversal` | [treasury.credit_reversal](treasury-credit-reversal.md) | No |  |
| `outbound_payment` | [treasury.outbound_payment](treasury-outbound-payment.md) | No |  |
| `outbound_transfer` | [treasury.outbound_transfer](treasury-outbound-transfer.md) | No |  |
| `payout` | [payout](payout.md) | No |  |
| `type` | enum: credit_reversal, other, outbound_payment... | Yes | The type of the source flow that originated the ReceivedCredit. |

