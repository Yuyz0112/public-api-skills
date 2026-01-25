# mconn_snapshot_mount

Snapshot Mount

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `available_bytes` | number | No | Available disk size (bytes) |
| `connector_id` | string | No | Connector identifier |
| `file_system` | string | Yes | File system on disk (EXT4, NTFS, etc.) |
| `is_read_only` | boolean | No | Determines whether the disk is read-only |
| `is_removable` | boolean | No | Determines whether the disk is removable |
| `kind` | string | Yes | Kind of disk (HDD, SSD, etc.) |
| `mount_point` | string | Yes | Path where disk is mounted |
| `name` | string | Yes | Name of the disk mount |
| `total_bytes` | number | No | Total disk size (bytes) |

