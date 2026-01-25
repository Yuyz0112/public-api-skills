# TargetUsersJobStatusResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | [TargetUsersJobStatusTypes](TargetUsersJobStatusTypes.md) | Yes |  |
| `total_users` | [UInt32Type](UInt32Type.md) | Yes |  |
| `processed_users` | [UInt32Type](UInt32Type.md) | Yes |  |
| `created_at` | string,null (date-time) | No | The timestamp when the job was created. |
| `completed_at` | string,null (date-time) | No | The timestamp when the job was successfully completed. |
| `error_message` | string,null | No | The error message if the job failed. |

