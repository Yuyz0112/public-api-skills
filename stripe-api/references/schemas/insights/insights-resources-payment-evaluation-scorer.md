# insights_resources_payment_evaluation_scorer

Scores, insights and recommended action for one scorer for this PaymentEvaluation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `recommended_action` | enum: block, continue | Yes | Recommended action based on the risk score. Possible values are `block` and `continue`. |
| `risk_score` | integer | Yes | Stripe Radar’s evaluation of the risk level of the payment. Possible values for evaluated payments are between 0 and 100, with higher scores indicating higher risk. |

