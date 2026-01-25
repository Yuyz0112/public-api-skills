# AuditLogEventResource

The primary object that was affected by this event.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resource_type` | string | No | The type of resource. |
| `resource_subtype` | string | No | The subtype of resource. Most resources will not have a subtype. |
| `gid` | string | No | Globally unique identifier of the resource. |
| `name` | string | No | The name of the resource. |
| `email` | string | No | The email of the resource, if applicable. |

