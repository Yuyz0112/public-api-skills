# balance_settings_resource_payments

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `debit_negative_balances` | boolean | No | A Boolean indicating if Stripe should try to reclaim negative balances from an attached bank account. See [Understanding Connect account balances](/connect/account-balances) for details. The default value is `false` when [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `application`, which includes Custom accounts, otherwise `true`. |
| `payouts` | any | No | Settings specific to the account's payouts. |
| `settlement_timing` | [balance_settings_resource_settlement_timing](balance-settings-resource-settlement-timing.md) | Yes |  |

