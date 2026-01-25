# firewall_cidr_configuration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target` | enum: ip_range | No | The configuration target. You must set the target to `ip_range` when specifying an IP address range in the rule. |
| `value` | string | No | The IP address range to match. You can only use prefix lengths `/16` and `/24` for IPv4 ranges, and prefix lengths `/32`, `/48`, and `/64` for IPv6 ranges. |

