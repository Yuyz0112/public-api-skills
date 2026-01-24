# financial_connections.session

A Financial Connections Session is the secure way to programmatically launch the client-side Stripe.js modal that lets your users link their accounts.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder` | any | No | The account holder for whom accounts are collected in this session. |
| `accounts` | object | Yes | The accounts that were collected as part of this Session. |
| `client_secret` | string | No | A value that will be passed to the client to launch the authentication flow. |
| `filters` | [bank_connections_resource_link_account_session_filters](bank-connections-resource-link-account-session-filters.md) | No |  |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: financial_connections.session | Yes | String representing the object's type. Objects of the same type share the same value. |
| `permissions` | string[] | Yes | Permissions requested for accounts collected during this session. |
| `prefetch` | string[] | No | Data features requested to be retrieved upon account creation. |
| `return_url` | string | No | For webview integrations only. Upon completing OAuth login in the native browser, the user will be redirected to this URL to return to your app. |

## Nested Fields

### `accounts`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | financial_connections.account[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

