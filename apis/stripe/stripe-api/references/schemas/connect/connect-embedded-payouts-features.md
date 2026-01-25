# connect_embedded_payouts_features

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `disable_stripe_user_authentication` | boolean | Yes | Whether Stripe user authentication is disabled. This value can only be `true` for accounts where `controller.requirement_collection` is `application` for the account. The default value is the opposite of the `external_account_collection` value. For example, if you don't set `external_account_collection`, it defaults to `true` and `disable_stripe_user_authentication` defaults to `false`. |
| `edit_payout_schedule` | boolean | Yes | Whether to allow payout schedule to be changed. Defaults to `true` when `controller.losses.payments` is set to `stripe` for the account, otherwise `false`. |
| `external_account_collection` | boolean | Yes | Whether external account collection is enabled. This feature can only be `false` for accounts where you’re responsible for collecting updated information when requirements are due or change, like Custom accounts. The default value for this feature is `true`. |
| `instant_payouts` | boolean | Yes | Whether to allow creation of instant payouts. The default value is `enabled` when Stripe is responsible for negative account balances, and `use_dashboard_rules` otherwise. |
| `standard_payouts` | boolean | Yes | Whether to allow creation of standard payouts. Defaults to `true` when `controller.losses.payments` is set to `stripe` for the account, otherwise `false`. |

