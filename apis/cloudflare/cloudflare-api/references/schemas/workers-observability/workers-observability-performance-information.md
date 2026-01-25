# workers-observability_performance_information

The statistics object contains information about query performance from the database, it does not include any network latency

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `abr_level` | number | No | The level of Adaptive Bit Rate (ABR) sampling used for the query. If empty the ABR level is 1 |
| `bytes_read` | number | Yes | Number of uncompressed bytes read from the table. |
| `elapsed` | number | Yes | Time in seconds for the query to run. |
| `rows_read` | number | Yes | Number of rows scanned from the table. |

