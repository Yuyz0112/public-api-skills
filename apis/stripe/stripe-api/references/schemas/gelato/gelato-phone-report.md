# gelato_phone_report

Result from a phone check

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `error` | any | No | Details on the verification error. Present when status is `unverified`. |
| `phone` | string | No | Phone to be verified. |
| `status` | enum: unverified, verified | Yes | Status of this `phone` check. |

