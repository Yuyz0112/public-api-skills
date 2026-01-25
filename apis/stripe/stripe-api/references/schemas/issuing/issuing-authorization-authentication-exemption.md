# issuing_authorization_authentication_exemption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `claimed_by` | enum: acquirer, issuer | Yes | The entity that requested the exemption, either the acquiring merchant or the Issuing user. |
| `type` | enum: low_value_transaction, transaction_risk_analysis, unknown | Yes | The specific exemption claimed for this authorization. |

