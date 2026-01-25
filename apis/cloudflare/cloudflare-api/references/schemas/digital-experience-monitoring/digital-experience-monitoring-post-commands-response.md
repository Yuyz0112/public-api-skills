# digital-experience-monitoring_post_commands_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `commands` | object[] | No | List of created commands |

## Nested Fields

### `commands`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `args` | object | No | Command arguments |
| `device_id` | string | No | Identifier for the device associated with the command |
| `id` | string | No | Unique identifier for the command |
| `status` | enum: PENDING_EXEC, PENDING_UPLOAD, SUCCESS... | No | Current status of the command |
| `type` | string | No | Type of the command (e.g., "pcap" or "warp-diag") |

