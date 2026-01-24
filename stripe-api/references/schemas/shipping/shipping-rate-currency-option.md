# shipping_rate_currency_option

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | A non-negative integer in cents representing how much to charge. |
| `tax_behavior` | enum: exclusive, inclusive, unspecified | Yes | Specifies whether the rate is considered inclusive of taxes or exclusive of taxes. One of `inclusive`, `exclusive`, or `unspecified`. |

