# treasury.financial_account_features

Encodes whether a FinancialAccount has access to a particular Feature, with a `status` enum and associated `status_details`.
Stripe or the platform can control Features via the requested field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `card_issuing` | [treasury_financial_accounts_resource_toggle_settings](treasury-financial-accounts-resource-toggle-settings.md) | No |  |
| `deposit_insurance` | [treasury_financial_accounts_resource_toggle_settings](treasury-financial-accounts-resource-toggle-settings.md) | No |  |
| `financial_addresses` | [treasury_financial_accounts_resource_financial_addresses_features](treasury-financial-accounts-resource-financial-addresses-features.md) | No |  |
| `inbound_transfers` | [treasury_financial_accounts_resource_inbound_transfers](treasury-financial-accounts-resource-inbound-transfers.md) | No |  |
| `intra_stripe_flows` | [treasury_financial_accounts_resource_toggle_settings](treasury-financial-accounts-resource-toggle-settings.md) | No |  |
| `object` | enum: treasury.financial_account_features | Yes | String representing the object's type. Objects of the same type share the same value. |
| `outbound_payments` | [treasury_financial_accounts_resource_outbound_payments](treasury-financial-accounts-resource-outbound-payments.md) | No |  |
| `outbound_transfers` | [treasury_financial_accounts_resource_outbound_transfers](treasury-financial-accounts-resource-outbound-transfers.md) | No |  |

