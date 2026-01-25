# gelato_email_report

Result from a email check

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | string | No | Email to be verified. |
| `error` | any | No | Details on the verification error. Present when status is `unverified`. |
| `status` | enum: unverified, verified | Yes | Status of this `email` check. |

