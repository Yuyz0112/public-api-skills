# external_account_requirements

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `currently_due` | string[] | No | Fields that need to be resolved to keep the external account enabled. If not resolved by `current_deadline`, these fields will appear in `past_due` as well, and the account is disabled. |
| `errors` | account_requirements_error[] | No | Details about validation and verification failures for `due` requirements that must be resolved. |
| `past_due` | string[] | No | Fields that haven't been resolved by `current_deadline`. These fields need to be resolved to enable the external account. |
| `pending_verification` | string[] | No | Fields that are being reviewed, or might become required depending on the results of a review. If the review fails, these fields can move to `eventually_due`, `currently_due`, `past_due` or `alternatives`. Fields might appear in `eventually_due`, `currently_due`, `past_due` or `alternatives` and in `pending_verification` if one verification fails but another is still pending. |

