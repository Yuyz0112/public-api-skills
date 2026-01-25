# ProjectMembershipCompact

This object describes a team or a user's membership to a project including their level of access (Admin, Editor, Commenter, or Viewer).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `parent` | [ProjectCompact](ProjectCompact.md) | No |  |
| `member` | [MemberCompact](MemberCompact.md) | No |  |
| `access_level` | enum: admin, editor, commenter... | No | Whether the member has admin, editor, commenter, or viewer access to the project. |

