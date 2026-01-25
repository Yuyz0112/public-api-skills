# UserCompact

A *user* object represents an account in Asana that can be given access to various workspaces, projects, and tasks.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `name` | string | No | *Read-only except when same user as requester*. The user's name. |

