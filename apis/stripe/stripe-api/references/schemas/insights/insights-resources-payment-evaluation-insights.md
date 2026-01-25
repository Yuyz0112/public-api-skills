# insights_resources_payment_evaluation_insights

Collection of scores and insights for this payment evaluation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `card_issuer_decline` | any | No | Stripe Radar's evaluation of the likelihood of a card issuer decline on this payment. |
| `evaluated_at` | integer (unix-time) | Yes | The timestamp when the evaluation was performed. |
| `fraudulent_dispute` | [insights_resources_payment_evaluation_scorer](insights-resources-payment-evaluation-scorer.md) | Yes |  |

