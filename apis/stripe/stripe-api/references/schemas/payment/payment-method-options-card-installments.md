# payment_method_options_card_installments

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `available_plans` | payment_method_details_card_installments_plan[] | No | Installment plans that may be selected for this PaymentIntent. |
| `enabled` | boolean | Yes | Whether Installments are enabled for this PaymentIntent. |
| `plan` | any | No | Installment plan selected for this PaymentIntent. |

