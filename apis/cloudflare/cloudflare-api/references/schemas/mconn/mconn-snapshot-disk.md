# mconn_snapshot_disk

Snapshot Disk

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `connector_id` | string | No | Connector identifier |
| `discards` | number | No | Discards completed successfully |
| `discards_merged` | number | No | Discards merged |
| `flushes` | number | No | Flushes completed successfully |
| `in_progress` | number | Yes | I/Os currently in progress |
| `major` | number | Yes | Device major number |
| `merged` | number | Yes | Reads merged |
| `minor` | number | Yes | Device minor number |
| `name` | string | Yes | Device name |
| `reads` | number | Yes | Reads completed successfully |
| `sectors_discarded` | number | No | Sectors discarded |
| `sectors_read` | number | Yes | Sectors read successfully |
| `sectors_written` | number | Yes | Sectors written successfully |
| `time_discarding_ms` | number | No | Time spent discarding (milliseconds) |
| `time_flushing_ms` | number | No | Time spent flushing (milliseconds) |
| `time_in_progress_ms` | number | Yes | Time spent doing I/Os (milliseconds) |
| `time_reading_ms` | number | Yes | Time spent reading (milliseconds) |
| `time_writing_ms` | number | Yes | Time spent writing (milliseconds) |
| `weighted_time_in_progress_ms` | number | Yes | Weighted time spent doing I/Os (milliseconds) |
| `writes` | number | Yes | Writes completed |
| `writes_merged` | number | Yes | Writes merged |

