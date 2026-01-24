# linked_account_options_common

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `filters` | [payment_flows_private_payment_methods_financial_connections_common_linked_account_options_filters](payment-flows-private-payment-methods-financial-connections-common-linked-account-options-filters.md) | No |  |
| `permissions` | string[] | No | The list of permissions to request. The `payment_method` permission must be included. |
| `prefetch` | string[] | No | Data features requested to be retrieved upon account creation. |
| `return_url` | string | No | For webview integrations only. Upon completing OAuth login in the native browser, the user will be redirected to this URL to return to your app. |

