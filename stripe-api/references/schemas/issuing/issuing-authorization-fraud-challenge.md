# issuing_authorization_fraud_challenge

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `channel` | enum: sms | Yes | The method by which the fraud challenge was delivered to the cardholder. |
| `status` | enum: expired, pending, rejected... | Yes | The status of the fraud challenge. |
| `undeliverable_reason` | enum: no_phone_number, unsupported_phone_number | No | If the challenge is not deliverable, the reason why. |

