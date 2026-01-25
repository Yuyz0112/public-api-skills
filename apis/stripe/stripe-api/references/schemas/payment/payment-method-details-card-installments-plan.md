# payment_method_details_card_installments_plan

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | integer | No | For `fixed_count` installment plans, this is the number of installment payments your customer will make to their credit card. |
| `interval` | enum: month | No | For `fixed_count` installment plans, this is the interval between installment payments your customer will make to their credit card.
One of `month`. |
| `type` | enum: bonus, fixed_count, revolving | Yes | Type of installment plan, one of `fixed_count`, `bonus`, or `revolving`. |

