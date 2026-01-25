# api-shield_selector

Select operations covered by this rule.

For details on selectors, see the [Cloudflare Docs](https://developers.cloudflare.com/api-shield/security/jwt-validation/).


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `exclude` | api-shield_selector-exclude[] | No | Ignore operations that were otherwise included by `include`. |
| `include` | api-shield_selector-include[] | No | Select all matching operations. |

