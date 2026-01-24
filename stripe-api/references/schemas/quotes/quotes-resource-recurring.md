# quotes_resource_recurring

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_subtotal` | integer | Yes | Total before any discounts or taxes are applied. |
| `amount_total` | integer | Yes | Total after discounts and taxes are applied. |
| `interval` | enum: day, month, week... | Yes | The frequency at which a subscription is billed. One of `day`, `week`, `month` or `year`. |
| `interval_count` | integer | Yes | The number of intervals (specified in the `interval` attribute) between subscription billings. For example, `interval=month` and `interval_count=3` bills every 3 months. |
| `total_details` | [quotes_resource_total_details](quotes-resource-total-details.md) | Yes |  |

