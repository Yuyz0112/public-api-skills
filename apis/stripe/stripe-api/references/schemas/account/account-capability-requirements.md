# account_capability_requirements

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alternatives` | account_requirements_alternative[] | No | Fields that are due and can be resolved by providing the corresponding alternative fields instead. Multiple alternatives can reference the same `original_fields_due`. When this happens, any of these alternatives can serve as a pathway for attempting to resolve the fields. Additionally, providing `original_fields_due` again also serves as a pathway for attempting to resolve the fields. |
| `current_deadline` | integer (unix-time) | No | The date by which all required account information must be both submitted and verified. This includes fields listed in `currently_due` as well as those in `pending_verification`. If any required information is missing or unverified by this date, the account may be disabled. Note that `current_deadline` may change if additional `currently_due` requirements are requested. |
| `currently_due` | string[] | Yes | Fields that need to be resolved to keep the capability enabled. If not resolved by `current_deadline`, these fields will appear in `past_due` as well, and the capability is disabled. |
| `disabled_reason` | enum: other, paused.inactivity, pending.onboarding... | No | Description of why the capability is disabled. [Learn more about handling verification issues](https://docs.stripe.com/connect/handling-api-verification). |
| `errors` | account_requirements_error[] | Yes | Details about validation and verification failures for `due` requirements that must be resolved. |
| `eventually_due` | string[] | Yes | Fields you must collect when all thresholds are reached. As they become required, they appear in `currently_due` as well, and `current_deadline` becomes set. |
| `past_due` | string[] | Yes | Fields that haven't been resolved by `current_deadline`. These fields need to be resolved to enable the capability on the account. |
| `pending_verification` | string[] | Yes | Fields that are being reviewed, or might become required depending on the results of a review. If the review fails, these fields can move to `eventually_due`, `currently_due`, `past_due` or `alternatives`. Fields might appear in `eventually_due`, `currently_due`, `past_due` or `alternatives` and in `pending_verification` if one verification fails but another is still pending. |

