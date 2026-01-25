# network-settings

A hosted compute network settings resource.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The unique identifier of the network settings resource. |
| `network_configuration_id` | string | No | The identifier of the network configuration that is using this settings resource. |
| `name` | string | Yes | The name of the network settings resource. |
| `subnet_id` | string | Yes | The subnet this network settings resource is configured for. |
| `region` | string | Yes | The location of the subnet this network settings resource is configured for. |

