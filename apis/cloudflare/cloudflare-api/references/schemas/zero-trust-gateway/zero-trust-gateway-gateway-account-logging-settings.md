# zero-trust-gateway_gateway-account-logging-settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `redact_pii` | boolean | No | Indicate whether to redact personally identifiable information from activity logging (PII fields include source IP, user email, user ID, device ID, URL, referrer, and user agent). |
| `settings_by_rule_type` | object | No | Configure logging settings for each rule type. |

## Nested Fields

### `settings_by_rule_type`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dns` | any | No | Configure logging settings for DNS firewall. |
| `http` | any | No | Configure logging settings for HTTP/HTTPS firewall. |
| `l4` | any | No | Configure logging settings for Network firewall. |

