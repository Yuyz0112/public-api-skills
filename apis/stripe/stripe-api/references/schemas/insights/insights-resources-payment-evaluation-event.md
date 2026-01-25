# insights_resources_payment_evaluation_event

Event reported for this payment evaluation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dispute_opened` | [insights_resources_payment_evaluation_dispute_opened](insights-resources-payment-evaluation-dispute-opened.md) | No |  |
| `early_fraud_warning_received` | [insights_resources_payment_evaluation_early_fraud_warning_received](insights-resources-payment-evaluation-early-fraud-warning-received.md) | No |  |
| `occurred_at` | integer (unix-time) | Yes | Timestamp when the event occurred. |
| `refunded` | [insights_resources_payment_evaluation_refunded](insights-resources-payment-evaluation-refunded.md) | No |  |
| `type` | enum: dispute_opened, early_fraud_warning_received, refunded... | Yes | Indicates the type of event attached to the payment evaluation. |
| `user_intervention_raised` | [insights_resources_payment_evaluation_user_intervention_raised](insights-resources-payment-evaluation-user-intervention-raised.md) | No |  |
| `user_intervention_resolved` | [insights_resources_payment_evaluation_user_intervention_resolved](insights-resources-payment-evaluation-user-intervention-resolved.md) | No |  |

