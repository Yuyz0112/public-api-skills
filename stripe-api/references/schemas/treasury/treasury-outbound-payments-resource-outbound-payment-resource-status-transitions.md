# treasury_outbound_payments_resource_outbound_payment_resource_status_transitions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `canceled_at` | integer (unix-time) | No | Timestamp describing when an OutboundPayment changed status to `canceled`. |
| `failed_at` | integer (unix-time) | No | Timestamp describing when an OutboundPayment changed status to `failed`. |
| `posted_at` | integer (unix-time) | No | Timestamp describing when an OutboundPayment changed status to `posted`. |
| `returned_at` | integer (unix-time) | No | Timestamp describing when an OutboundPayment changed status to `returned`. |

