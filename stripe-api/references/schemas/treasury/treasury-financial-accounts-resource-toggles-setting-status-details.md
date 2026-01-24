# treasury_financial_accounts_resource_toggles_setting_status_details

Additional details on the FinancialAccount Features information.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | enum: activating, capability_not_requested, financial_account_closed... | Yes | Represents the reason why the status is `pending` or `restricted`. |
| `resolution` | enum: contact_stripe, provide_information, remove_restriction | No | Represents what the user should do, if anything, to activate the Feature. |
| `restriction` | enum: inbound_flows, outbound_flows | No | The `platform_restrictions` that are restricting this Feature. |

