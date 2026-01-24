# issuing_card_fraud_warning

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `started_at` | integer (unix-time) | No | Timestamp of the most recent fraud warning. |
| `type` | enum: card_testing_exposure, fraud_dispute_filed, third_party_reported... | No | The type of fraud warning that most recently took place on this card. This field updates with every new fraud warning, so the value changes over time. If populated, cancel and reissue the card. |

