# dns-custom-nameservers_CustomNS

A single account custom nameserver.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dns_records` | object[] | Yes | A and AAAA records associated with the nameserver. |
| `ns_name` | [dns-custom-nameservers_ns_name](dns-custom-nameservers-ns-name.md) | Yes |  |
| `ns_set` | [dns-custom-nameservers_ns_set](dns-custom-nameservers-ns-set.md) | No |  |
| `status` | enum: moved, pending, verified | Yes | Verification status of the nameserver. |
| `zone_tag` | [dns-custom-nameservers_schemas-identifier](dns-custom-nameservers-schemas-identifier.md) | Yes |  |

## Nested Fields

### `dns_records`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: A, AAAA | No | DNS record type. |
| `value` | string | No | DNS record contents (an IPv4 or IPv6 address). |

