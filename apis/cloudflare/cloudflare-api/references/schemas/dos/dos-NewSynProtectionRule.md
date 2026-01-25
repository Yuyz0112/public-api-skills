# dos_NewSynProtectionRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `burst_sensitivity` | string | Yes | The burst sensitivity. Must be one of 'low', 'medium', 'high'. |
| `mitigation_type` | string | No | The type of mitigation. Must be one of 'challenge' or 'retransmit'. Optional. Defaults to 'challenge'. |
| `mode` | string | Yes | The mode for SYN Protection. Must be one of 'enabled', 'disabled', 'monitoring'. |
| `name` | string | Yes | The name of the SYN Protection rule. Value is relative to the 'scope' setting. For 'global' scope, name should be 'global'. For either the 'region' or 'datacenter' scope, name should be the actual name of the region or datacenter, e.g., 'wnam' or 'lax'. |
| `rate_sensitivity` | string | Yes | The rate sensitivity. Must be one of 'low', 'medium', 'high'. |
| `scope` | string | Yes | The scope for the SYN Protection rule. Must be one of 'global', 'region', or 'datacenter'. |

