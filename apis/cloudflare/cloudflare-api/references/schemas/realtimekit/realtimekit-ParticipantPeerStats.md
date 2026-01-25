# realtimekit_ParticipantPeerStats

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `peer_stats` | object | No |  |

## Nested Fields

### `peer_stats`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config` | string | No |  |
| `device_info` | object | No |  |
| `events` | object[] | No |  |
| `ip_information` | object | No |  |
| `precall_network_information` | object | No |  |
| `status` | string | No |  |

#### `peer_stats.device_info`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `browser` | string | No |  |
| `browser_version` | string | No |  |
| `cpus` | number | No |  |
| `engine` | string | No |  |
| `is_mobile` | boolean | No |  |
| `memory` | number | No |  |
| `os` | string | No |  |
| `os_version` | string | No |  |
| `sdk_name` | string | No |  |
| `sdk_version` | string | No |  |
| `user_agent` | string | No |  |
| `webgl_support` | string | No |  |

#### `peer_stats.events`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timestamp` | string | No |  |
| `type` | string | No |  |

#### `peer_stats.ip_information`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `city` | string | No |  |
| `country` | string | No |  |
| `ip_location` | string | No |  |
| `ipv4` | string | No |  |
| `org` | string | No |  |
| `portal` | string | No |  |
| `region` | string | No |  |
| `timezone` | string | No |  |

#### `peer_stats.precall_network_information`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `backend_rtt` | number | No |  |
| `effective_networktype` | string | No |  |
| `fractional_loss` | number | No |  |
| `jitter` | number | No |  |
| `reflexive_connectivity` | boolean | No |  |
| `relay_connectivity` | boolean | No |  |
| `rtt` | number | No |  |
| `throughtput` | number | No |  |
| `turn_connectivity` | boolean | No |  |

