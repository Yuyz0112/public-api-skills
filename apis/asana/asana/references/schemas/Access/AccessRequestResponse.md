# AccessRequestResponse

A *access request* object represents a request to access a shareable resource within Asana. It includes the requester's information, approval status, and target resource details.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `message` | string | No | The message included in the access request, if any. |
| `approval_status` | enum: pending, approved, denied | No | The current approval status of the request. |
| `requester` | [UserCompact](UserCompact.md) | No |  |
| `target` | [AccessRequestTargetIdCompact](AccessRequestTargetIdCompact.md) | No |  |

