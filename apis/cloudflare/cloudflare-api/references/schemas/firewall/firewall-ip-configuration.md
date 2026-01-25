# firewall_ip_configuration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target` | enum: ip | No | The configuration target. You must set the target to `ip` when specifying an IP address in the rule. |
| `value` | string | No | The IP address to match. This address will be compared to the IP address of incoming requests. |

