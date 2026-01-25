# insights_resources_payment_evaluation_outcome

Outcome details for this payment evaluation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `merchant_blocked` | [insights_resources_payment_evaluation_merchant_blocked](insights-resources-payment-evaluation-merchant-blocked.md) | No |  |
| `payment_intent_id` | string | No | The PaymentIntent ID associated with the payment evaluation. |
| `rejected` | [insights_resources_payment_evaluation_rejected](insights-resources-payment-evaluation-rejected.md) | No |  |
| `succeeded` | [insights_resources_payment_evaluation_succeeded](insights-resources-payment-evaluation-succeeded.md) | No |  |
| `type` | enum: failed, merchant_blocked, rejected... | Yes | Indicates the outcome of the payment evaluation. |

