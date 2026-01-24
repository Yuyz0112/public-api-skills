# issuing_authorization_treasury

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `received_credits` | string[] | Yes | The array of [ReceivedCredits](https://docs.stripe.com/api/treasury/received_credits) associated with this authorization |
| `received_debits` | string[] | Yes | The array of [ReceivedDebits](https://docs.stripe.com/api/treasury/received_debits) associated with this authorization |
| `transaction` | string | No | The Treasury [Transaction](https://docs.stripe.com/api/treasury/transactions) associated with this authorization |

