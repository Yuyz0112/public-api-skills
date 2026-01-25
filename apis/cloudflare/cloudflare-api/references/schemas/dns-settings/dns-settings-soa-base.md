# dns-settings_soa-base

Components of the zone's SOA record.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expire` | number | No | Time in seconds of being unable to query the primary server after which secondary servers should stop serving the zone. |
| `min_ttl` | number | No | The time to live (TTL) for negative caching of records within the zone. |
| `mname` | string | No | The primary nameserver, which may be used for outbound zone transfers. If null, a Cloudflare-assigned value will be used. |
| `refresh` | number | No | Time in seconds after which secondary servers should re-check the SOA record to see if the zone has been updated. |
| `retry` | number | No | Time in seconds after which secondary servers should retry queries after the primary server was unresponsive. |
| `rname` | string | No | The email address of the zone administrator, with the first label representing the local part of the email address. |
| `ttl` | number | No | The time to live (TTL) of the SOA record itself. |

