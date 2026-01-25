# rulesets_SetCacheSettingsBrowserTTL

How long client browsers should cache the response. Cloudflare cache purge will not purge content cached on client browsers, so high browser TTLs may lead to stale content.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default` | integer | No | The browser TTL (in seconds) if you choose the "override_origin" mode. |
| `mode` | enum: respect_origin, bypass_by_default, override_origin... | Yes | The browser TTL mode. |

