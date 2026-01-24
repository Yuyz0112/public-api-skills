# tax_deducted_at_source

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Unique identifier for the object. |
| `object` | enum: tax_deducted_at_source | Yes | String representing the object's type. Objects of the same type share the same value. |
| `period_end` | integer (unix-time) | Yes | The end of the invoicing period. This TDS applies to Stripe fees collected during this invoicing period. |
| `period_start` | integer (unix-time) | Yes | The start of the invoicing period. This TDS applies to Stripe fees collected during this invoicing period. |
| `tax_deduction_account_number` | string | Yes | The TAN that was supplied to Stripe when TDS was assessed |

