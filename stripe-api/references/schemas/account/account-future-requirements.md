# account_future_requirements

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alternatives` | account_requirements_alternative[] | No | Fields that are due and can be resolved by providing the corresponding alternative fields instead. Many alternatives can list the same `original_fields_due`, and any of these alternatives can serve as a pathway for attempting to resolve the fields again. Re-providing `original_fields_due` also serves as a pathway for attempting to resolve the fields again. |
| `current_deadline` | integer (unix-time) | No | Date on which `future_requirements` becomes the main `requirements` hash and `future_requirements` becomes empty. After the transition, `currently_due` requirements may immediately become `past_due`, but the account may also be given a grace period depending on its enablement state prior to transitioning. |
| `currently_due` | string[] | No | Fields that need to be resolved to keep the account enabled. If not resolved by `future_requirements[current_deadline]`, these fields will transition to the main `requirements` hash. |
| `disabled_reason` | enum: action_required.requested_capabilities, listed, other... | No | This is typed as an enum for consistency with `requirements.disabled_reason`. |
| `errors` | account_requirements_error[] | No | Details about validation and verification failures for `due` requirements that must be resolved. |
| `eventually_due` | string[] | No | Fields you must collect when all thresholds are reached. As they become required, they appear in `currently_due` as well. |
| `past_due` | string[] | No | Fields that haven't been resolved by `requirements.current_deadline`. These fields need to be resolved to enable the capability on the account. `future_requirements.past_due` is a subset of `requirements.past_due`. |
| `pending_verification` | string[] | No | Fields that are being reviewed, or might become required depending on the results of a review. If the review fails, these fields can move to `eventually_due`, `currently_due`, `past_due` or `alternatives`. Fields might appear in `eventually_due`, `currently_due`, `past_due` or `alternatives` and in `pending_verification` if one verification fails but another is still pending. |

