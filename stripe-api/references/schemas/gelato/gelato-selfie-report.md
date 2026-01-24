# gelato_selfie_report

Result from a selfie check

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `document` | string | No | ID of the [File](https://docs.stripe.com/api/files) holding the image of the identity document used in this check. |
| `error` | any | No | Details on the verification error. Present when status is `unverified`. |
| `selfie` | string | No | ID of the [File](https://docs.stripe.com/api/files) holding the image of the selfie used in this check. |
| `status` | enum: unverified, verified | Yes | Status of this `selfie` check. |

