# network-configuration

A hosted compute network configuration.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The unique identifier of the network configuration. |
| `name` | string | Yes | The name of the network configuration. |
| `compute_service` | enum: none, actions, codespaces | No | The hosted compute service the network configuration supports. |
| `network_settings_ids` | string[] | No | The unique identifier of each network settings in the configuration. |
| `failover_network_settings_ids` | string[] | No | The unique identifier of each failover network settings in the configuration. |
| `failover_network_enabled` | boolean | No | Indicates whether the failover network resource is enabled. |
| `created_on` | string (date-time) | Yes | The time at which the network configuration was created, in ISO 8601 format. |

