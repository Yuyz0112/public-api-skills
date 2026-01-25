# secret-scanning-scan

Information on a single scan performed by secret scanning on the repository

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No | The type of scan |
| `status` | string | No | The state of the scan. Either "completed", "running", or "pending" |
| `completed_at` | string (date-time) | No | The time that the scan was completed. Empty if the scan is running |
| `started_at` | string (date-time) | No | The time that the scan was started. Empty if the scan is pending |

