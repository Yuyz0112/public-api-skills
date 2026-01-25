# dos_NewTcpFlowProtectionRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `burst_sensitivity` | string | Yes | The burst sensitivity. Must be one of 'low', 'medium', 'high'. |
| `mode` | string | Yes | The mode for the TCP Flow Protection. Must be one of 'enabled', 'disabled', 'monitoring'. |
| `name` | string | Yes | The name of the TCP Flow Protection rule. Value is relative to the 'scope' setting. For 'global' scope, name should be 'global'. For either the 'region' or 'datacenter' scope, name should be the actual name of the region or datacenter, e.g., 'wnam' or 'lax'. |
| `rate_sensitivity` | string | Yes | The rate sensitivity. Must be one of 'low', 'medium', 'high'. |
| `scope` | string | Yes | The scope for the TCP Flow Protection rule. |

