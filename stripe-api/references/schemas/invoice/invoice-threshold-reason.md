# invoice_threshold_reason

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_gte` | integer | No | The total invoice amount threshold boundary if it triggered the threshold invoice. |
| `item_reasons` | invoice_item_threshold_reason[] | Yes | Indicates which line items triggered a threshold invoice. |

