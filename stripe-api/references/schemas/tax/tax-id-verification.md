# tax_id_verification

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: pending, unavailable, unverified... | Yes | Verification status, one of `pending`, `verified`, `unverified`, or `unavailable`. |
| `verified_address` | string | No | Verified address. |
| `verified_name` | string | No | Verified name. |

