# AuditLogEvent

An object representing a single event within an Asana domain.

Every audit log event is comprised of an `event_type`, `actor`, `resource`, and `context`. Some events will include additional metadata about the event under `details`. See our [currently supported list of events](/docs/audit-log-events#supported-audit-log-events) for more details.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the `AuditLogEvent`, as a string. |
| `created_at` | string (date-time) | No | The time the event was created. |
| `event_type` | string | No | The type of the event. |
| `event_category` | string | No | The category that this `event_type` belongs to. |
| `actor` | [AuditLogEventActor](AuditLogEventActor.md) | No |  |
| `resource` | [AuditLogEventResource](AuditLogEventResource.md) | No |  |
| `details` | [AuditLogEventDetails](AuditLogEventDetails.md) | No |  |
| `context` | [AuditLogEventContext](AuditLogEventContext.md) | No |  |

