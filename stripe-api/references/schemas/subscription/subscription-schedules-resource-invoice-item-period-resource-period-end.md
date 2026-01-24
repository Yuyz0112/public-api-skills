# subscription_schedules_resource_invoice_item_period_resource_period_end

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timestamp` | integer (unix-time) | No | A precise Unix timestamp for the end of the invoice item period. Must be greater than or equal to `period.start`. |
| `type` | enum: min_item_period_end, phase_end, timestamp | Yes | Select how to calculate the end of the invoice item period. |

