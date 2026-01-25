# invoice_mandate_options_card

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | No | Amount to be charged for future payments. |
| `amount_type` | enum: fixed, maximum | No | One of `fixed` or `maximum`. If `fixed`, the `amount` param refers to the exact amount to be charged in future payments. If `maximum`, the amount charged can be up to the value passed for the `amount` param. |
| `description` | string | No | A description of the mandate or subscription that is meant to be displayed to the customer. |

