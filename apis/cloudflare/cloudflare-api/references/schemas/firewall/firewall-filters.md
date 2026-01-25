# firewall_filters

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `configuration.target` | enum: ip, ip_range, asn... | No | The target to search in existing rules. |
| `configuration.value` | string | No | The target value to search for in existing rules: an IP address, an IP address range, or a country code, depending on the provided `configuration.target`.
Notes: You can search for a single IPv4 address, an IP address range with a subnet of '/16' or '/24', or a two-letter ISO-3166-1 alpha-2 country code. |
| `match` | enum: any, all | No | When set to `all`, all the search requirements must match. When set to `any`, only one of the search requirements has to match. |
| `mode` | [firewall_schemas-mode](firewall-schemas-mode.md) | No |  |
| `notes` | string | No | The string to search for in the notes of existing IP Access rules.
Notes: For example, the string 'attack' would match IP Access rules with notes 'Attack 26/02' and 'Attack 27/02'. The search is case insensitive. |

