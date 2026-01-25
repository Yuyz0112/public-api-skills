# transfer_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | No | The amount transferred to the destination account. This transfer will occur automatically after the payment succeeds. If no amount is specified, by default the entire payment amount is transferred to the destination account.
 The amount must be less than or equal to the [amount](https://docs.stripe.com/api/payment_intents/object#payment_intent_object-amount), and must be a positive integer
 representing how much to transfer in the smallest currency unit (e.g., 100 cents to charge $1.00). |
| `destination` | any | Yes | The account (if any) that the payment is attributed to for tax reporting, and where funds from the payment are transferred to after payment success. |

