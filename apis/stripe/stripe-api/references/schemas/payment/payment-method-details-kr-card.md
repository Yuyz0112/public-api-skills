# payment_method_details_kr_card

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `brand` | enum: bc, citi, hana... | No | The local credit or debit card brand. |
| `buyer_id` | string | No | A unique identifier for the buyer as determined by the local payment processor. |
| `last4` | string | No | The last four digits of the card. This may not be present for American Express cards. |
| `transaction_id` | string | No | The Korean Card transaction ID associated with this payment. |

