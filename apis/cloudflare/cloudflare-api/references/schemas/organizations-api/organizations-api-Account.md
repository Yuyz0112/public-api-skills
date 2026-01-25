# organizations-api_Account

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_on` | string (date-time) | Yes |  |
| `id` | string | Yes |  |
| `name` | string | Yes |  |
| `settings` | object | Yes |  |
| `type` | enum: standard, enterprise | Yes |  |

## Nested Fields

### `settings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `abuse_contact_email` | string | Yes |  |
| `access_approval_expiry` | string (date-time) | Yes |  |
| `api_access_enabled` | boolean | Yes |  |
| `default_nameservers` | string | Yes | Use [DNS Settings](https://developers.cloudflare.com/api/operations/dns-settings-for-an-account-list-dns-settings) instead. Deprecated. |
| `enforce_twofactor` | boolean | Yes |  |
| `use_account_custom_ns_by_default` | boolean | Yes | Use [DNS Settings](https://developers.cloudflare.com/api/operations/dns-settings-for-an-account-list-dns-settings) instead. Deprecated. |

