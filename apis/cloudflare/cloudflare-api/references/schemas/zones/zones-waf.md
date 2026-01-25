# zones_waf

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | enum: waf | No | Turn on or off [WAF managed rules (previous version, deprecated)](https://developers.cloudflare.com/waf/reference/legacy/old-waf-managed-rules/).
You cannot enable or disable individual WAF managed rules via Page Rules.
 |
| `value` | enum: on, off | No | The status of WAF managed rules (previous version).
 |

