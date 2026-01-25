# issuing_dispute_treasury

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `debit_reversal` | string | No | The Treasury [DebitReversal](https://docs.stripe.com/api/treasury/debit_reversals) representing this Issuing dispute |
| `received_debit` | string | Yes | The Treasury [ReceivedDebit](https://docs.stripe.com/api/treasury/received_debits) that is being disputed. |

