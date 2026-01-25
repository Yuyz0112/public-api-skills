# dos_TcpFlowProtectionRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `burst_sensitivity` | string | Yes | The burst sensitivity. Must be one of 'low', 'medium', 'high'. |
| `created_on` | string (date-time) | Yes | The creation timestamp of the TCP Flow Protection rule. |
| `id` | string | Yes | The unique ID of the TCP Flow Protection rule. |
| `mode` | string | Yes | The mode for TCP Flow Protection. Must be one of 'enabled', 'disabled', 'monitoring'. |
| `modified_on` | string (date-time) | Yes | The last modification timestamp of the TCP Flow Protection rule. |
| `name` | string | Yes | The name of the TCP Flow Protection rule. Value is relative to the 'scope' setting. For 'global' scope, name should be 'global'. For either the 'region' or 'datacenter' scope, name should be the actual name of the region or datacenter, e.g., 'wnam' or 'lax'. |
| `rate_sensitivity` | string | Yes | The rate sensitivity. Must be one of 'low', 'medium', 'high'. |
| `scope` | string | Yes | The scope for the TCP Flow Protection rule. Must be one of 'global', 'region', or 'datacenter'. |

