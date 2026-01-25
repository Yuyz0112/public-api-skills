# payment_method_options_card_mandate_options

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount to be charged for future payments. |
| `amount_type` | enum: fixed, maximum | Yes | One of `fixed` or `maximum`. If `fixed`, the `amount` param refers to the exact amount to be charged in future payments. If `maximum`, the amount charged can be up to the value passed for the `amount` param. |
| `description` | string | No | A description of the mandate or subscription that is meant to be displayed to the customer. |
| `end_date` | integer (unix-time) | No | End date of the mandate or subscription. If not provided, the mandate will be active until canceled. If provided, end date should be after start date. |
| `interval` | enum: day, month, sporadic... | Yes | Specifies payment frequency. One of `day`, `week`, `month`, `year`, or `sporadic`. |
| `interval_count` | integer | No | The number of intervals between payments. For example, `interval=month` and `interval_count=3` indicates one payment every three months. Maximum of one year interval allowed (1 year, 12 months, or 52 weeks). This parameter is optional when `interval=sporadic`. |
| `reference` | string | Yes | Unique identifier for the mandate or subscription. |
| `start_date` | integer (unix-time) | Yes | Start date of the mandate or subscription. Start date should not be lesser than yesterday. |
| `supported_types` | string[] | No | Specifies the type of mandates supported. Possible values are `india`. |

