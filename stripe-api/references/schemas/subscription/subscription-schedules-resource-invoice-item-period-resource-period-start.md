# subscription_schedules_resource_invoice_item_period_resource_period_start

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timestamp` | integer (unix-time) | No | A precise Unix timestamp for the start of the invoice item period. Must be less than or equal to `period.end`. |
| `type` | enum: max_item_period_start, phase_start, timestamp | Yes | Select how to calculate the start of the invoice item period. |

