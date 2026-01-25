# credit_note_refund

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_refunded` | integer | Yes | Amount of the refund that applies to this credit note, in cents (or local equivalent). |
| `payment_record_refund` | any | No | The PaymentRecord refund details associated with this credit note refund. |
| `refund` | any | Yes | ID of the refund. |
| `type` | enum: payment_record_refund, refund | No | Type of the refund, one of `refund` or `payment_record_refund`. |

