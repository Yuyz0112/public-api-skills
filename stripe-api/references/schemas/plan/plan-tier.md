# plan_tier

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `flat_amount` | integer | No | Price for the entire tier. |
| `flat_amount_decimal` | string (decimal) | No | Same as `flat_amount`, but contains a decimal value with at most 12 decimal places. |
| `unit_amount` | integer | No | Per unit price for units relevant to the tier. |
| `unit_amount_decimal` | string (decimal) | No | Same as `unit_amount`, but contains a decimal value with at most 12 decimal places. |
| `up_to` | integer | No | Up to and including to this quantity will be contained in the tier. |

