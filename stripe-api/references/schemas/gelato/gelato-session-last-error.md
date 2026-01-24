# gelato_session_last_error

Shows last VerificationSession error

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | enum: abandoned, consent_declined, country_not_supported... | No | A short machine-readable string giving the reason for the verification or user-session failure. |
| `reason` | string | No | A message that explains the reason for verification or user-session failure. |

