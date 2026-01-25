# rulesets_SetCacheSettingsEdgeTTL

How long the Cloudflare edge network should cache the response.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default` | integer | No | The edge TTL (in seconds) if you choose the "override_origin" mode. |
| `mode` | enum: respect_origin, bypass_by_default, override_origin | Yes | The edge TTL mode. |
| `status_code_ttl` | [rulesets_SetCacheSettingsStatusCodeTTL](rulesets-SetCacheSettingsStatusCodeTTL.md) | No |  |

