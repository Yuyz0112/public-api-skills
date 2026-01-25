# email_dns_record

List of records needed to enable an Email Routing zone.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content` | string | No | DNS record content. |
| `name` | string | No | DNS record name (or @ for the zone apex). |
| `priority` | number | No | Required for MX, SRV and URI records. Unused by other record types. Records with lower priorities are preferred. |
| `ttl` | number | No | Time to live, in seconds, of the DNS record. Must be between 60 and 86400, or 1 for 'automatic'. |
| `type` | enum: A, AAAA, CNAME... | No | DNS record type. |

