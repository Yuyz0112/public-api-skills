# invoice_item_threshold_reason

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `line_item_ids` | string[] | Yes | The IDs of the line items that triggered the threshold invoice. |
| `usage_gte` | integer | Yes | The quantity threshold boundary that applied to the given line item. |

