# GoalMembershipBase

This object represents a user's connection to a goal.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `resource_subtype` | string | No | The type of membership. |
| `member` | [MemberCompact](MemberCompact.md) | No |  |
| `parent` | any | No |  |
| `role` | enum: commenter, editor | No | *Deprecated: Describes if the member is a commenter or editor in goal.* |
| `access_level` | enum: viewer, commenter, editor... | No | "Describes the membership access level for the goal. This is preferred over role." |
| `goal` | any | No |  |

