# subscription_pending_invoice_item_interval

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `interval` | enum: day, month, week... | Yes | Specifies invoicing frequency. Either `day`, `week`, `month` or `year`. |
| `interval_count` | integer | Yes | The number of intervals between invoices. For example, `interval=month` and `interval_count=3` bills every 3 months. Maximum of one year interval allowed (1 year, 12 months, or 52 weeks). |

