# infra_IPInfo

The IPv4/IPv6 address that identifies where to reach a target

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ipv4` | object | No | The target's IPv4 address |
| `ipv6` | object | No | The target's IPv6 address |

## Nested Fields

### `ipv4`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ip_addr` | string | No | IP address of the target |
| `virtual_network_id` | string (uuid) | No | (optional) Private virtual network identifier for the target. If omitted, the default virtual network ID will be used. |

### `ipv6`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ip_addr` | string | No | IP address of the target |
| `virtual_network_id` | string (uuid) | No | (optional) Private virtual network identifier for the target. If omitted, the default virtual network ID will be used. |

