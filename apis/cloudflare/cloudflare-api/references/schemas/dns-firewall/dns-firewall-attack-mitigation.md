# dns-firewall_attack_mitigation

Attack mitigation settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | When enabled, automatically mitigate random-prefix attacks to protect upstream DNS servers |
| `only_when_upstream_unhealthy` | boolean | No | Only mitigate attacks when upstream servers seem unhealthy |

