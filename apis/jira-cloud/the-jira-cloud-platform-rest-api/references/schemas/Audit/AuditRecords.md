# AuditRecords

Container for a list of audit records.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `limit` | integer (int32) | No | The requested or default limit on the number of audit items to be returned. |
| `offset` | integer (int32) | No | The number of audit items skipped before the first item in this list. |
| `records` | AuditRecordBean[] | No | The list of audit items. |
| `total` | integer (int64) | No | The total number of audit items returned. |

