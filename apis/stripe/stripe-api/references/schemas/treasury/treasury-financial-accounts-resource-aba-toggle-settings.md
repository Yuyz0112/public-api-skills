# treasury_financial_accounts_resource_aba_toggle_settings

Toggle settings for enabling/disabling the ABA address feature

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `requested` | boolean | Yes | Whether the FinancialAccount should have the Feature. |
| `status` | enum: active, pending, restricted | Yes | Whether the Feature is operational. |
| `status_details` | treasury_financial_accounts_resource_toggles_setting_status_details[] | Yes | Additional details; includes at least one entry when the status is not `active`. |

