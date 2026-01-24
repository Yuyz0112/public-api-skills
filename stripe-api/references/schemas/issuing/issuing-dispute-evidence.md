# issuing_dispute_evidence

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `canceled` | [issuing_dispute_canceled_evidence](issuing-dispute-canceled-evidence.md) | No |  |
| `duplicate` | [issuing_dispute_duplicate_evidence](issuing-dispute-duplicate-evidence.md) | No |  |
| `fraudulent` | [issuing_dispute_fraudulent_evidence](issuing-dispute-fraudulent-evidence.md) | No |  |
| `merchandise_not_as_described` | [issuing_dispute_merchandise_not_as_described_evidence](issuing-dispute-merchandise-not-as-described-evidence.md) | No |  |
| `no_valid_authorization` | [issuing_dispute_no_valid_authorization_evidence](issuing-dispute-no-valid-authorization-evidence.md) | No |  |
| `not_received` | [issuing_dispute_not_received_evidence](issuing-dispute-not-received-evidence.md) | No |  |
| `other` | [issuing_dispute_other_evidence](issuing-dispute-other-evidence.md) | No |  |
| `reason` | enum: canceled, duplicate, fraudulent... | Yes | The reason for filing the dispute. Its value will match the field containing the evidence. |
| `service_not_as_described` | [issuing_dispute_service_not_as_described_evidence](issuing-dispute-service-not-as-described-evidence.md) | No |  |

