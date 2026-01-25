# issuing_cardholder_requirements

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `disabled_reason` | enum: listed, rejected.listed, requirements.past_due... | No | If `disabled_reason` is present, all cards will decline authorizations with `cardholder_verification_required` reason. |
| `past_due` | string[] | No | Array of fields that need to be collected in order to verify and re-enable the cardholder. |

