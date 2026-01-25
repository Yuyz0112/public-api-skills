# waf-product-api-bundle_custom-detection

Defines a custom set of username/password expressions to match Leaked Credential Checks on.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [waf-product-api-bundle_detection-id](waf-product-api-bundle-detection-id.md) | No |  |
| `password` | string | No | Defines ehe ruleset expression to use in matching the password in a request. |
| `username` | string | No | Defines the ruleset expression to use in matching the username in a request. |

