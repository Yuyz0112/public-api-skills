# insights_resources_payment_evaluation_card_issuer_decline

Provides Stripe Radar's evaluation of the likelihood that a payment will be declined by the card issuer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model_score` | number | Yes | Stripe Radar's evaluation of the likelihood that the payment will be declined by the card issuer. Scores range from 0 to 100, with higher values indicating a higher likelihood of decline. |
| `recommended_action` | enum: block, continue | Yes | Recommended action based on the model score. Possible values are `block` and `continue`. |

