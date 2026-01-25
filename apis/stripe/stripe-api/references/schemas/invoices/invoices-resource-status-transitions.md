# invoices_resource_status_transitions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `finalized_at` | integer (unix-time) | No | The time that the invoice draft was finalized. |
| `marked_uncollectible_at` | integer (unix-time) | No | The time that the invoice was marked uncollectible. |
| `paid_at` | integer (unix-time) | No | The time that the invoice was paid. |
| `voided_at` | integer (unix-time) | No | The time that the invoice was voided. |

