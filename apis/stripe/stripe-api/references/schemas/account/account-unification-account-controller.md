# account_unification_account_controller

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fees` | [account_unification_account_controller_fees](account-unification-account-controller-fees.md) | No |  |
| `is_controller` | boolean | No | `true` if the Connect application retrieving the resource controls the account and can therefore exercise [platform controls](https://docs.stripe.com/connect/platform-controls-for-standard-accounts). Otherwise, this field is null. |
| `losses` | [account_unification_account_controller_losses](account-unification-account-controller-losses.md) | No |  |
| `requirement_collection` | enum: application, stripe | No | A value indicating responsibility for collecting requirements on this account. Only returned when the Connect application retrieving the resource controls the account. |
| `stripe_dashboard` | [account_unification_account_controller_stripe_dashboard](account-unification-account-controller-stripe-dashboard.md) | No |  |
| `type` | enum: account, application | Yes | The controller type. Can be `application`, if a Connect application controls the account, or `account`, if the account controls itself. |

