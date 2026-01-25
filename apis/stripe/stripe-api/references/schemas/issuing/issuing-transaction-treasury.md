# issuing_transaction_treasury

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `received_credit` | string | No | The Treasury [ReceivedCredit](https://docs.stripe.com/api/treasury/received_credits) representing this Issuing transaction if it is a refund |
| `received_debit` | string | No | The Treasury [ReceivedDebit](https://docs.stripe.com/api/treasury/received_debits) representing this Issuing transaction if it is a capture |

