# AuditLogEntryResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `action_type` | [AuditLogActionTypes](AuditLogActionTypes.md) | Yes |  |
| `user_id` | any | No |  |
| `target_id` | any | No |  |
| `changes` | AuditLogObjectChangeResponse[] | No |  |
| `options` | object | No |  |
| `reason` | string | No |  |

