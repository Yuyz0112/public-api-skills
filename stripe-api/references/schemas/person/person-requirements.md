# person_requirements

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alternatives` | account_requirements_alternative[] | No | Fields that are due and can be resolved by providing the corresponding alternative fields instead. Many alternatives can list the same `original_fields_due`, and any of these alternatives can serve as a pathway for attempting to resolve the fields again. Re-providing `original_fields_due` also serves as a pathway for attempting to resolve the fields again. |
| `currently_due` | string[] | Yes | Fields that need to be resolved to keep the person's account enabled. If not resolved by the account's `current_deadline`, these fields will appear in `past_due` as well, and the account is disabled. |
| `errors` | account_requirements_error[] | Yes | Details about validation and verification failures for `due` requirements that must be resolved. |
| `eventually_due` | string[] | Yes | Fields you must collect when all thresholds are reached. As they become required, they appear in `currently_due` as well, and the account's `current_deadline` becomes set. |
| `past_due` | string[] | Yes | Fields that haven't been resolved by `current_deadline`. These fields need to be resolved to enable the person's account. |
| `pending_verification` | string[] | Yes | Fields that are being reviewed, or might become required depending on the results of a review. If the review fails, these fields can move to `eventually_due`, `currently_due`, `past_due` or `alternatives`. Fields might appear in `eventually_due`, `currently_due`, `past_due` or `alternatives` and in `pending_verification` if one verification fails but another is still pending. |

