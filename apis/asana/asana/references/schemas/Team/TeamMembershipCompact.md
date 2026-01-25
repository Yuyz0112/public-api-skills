# TeamMembershipCompact

This object represents a user's connection to a team.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `user` | [UserCompact](UserCompact.md) | No |  |
| `team` | [TeamCompact](TeamCompact.md) | No |  |
| `is_guest` | boolean | No | Describes if the user is a guest in the team. |
| `is_limited_access` | boolean | No | Describes if the user has limited access to the team. |
| `is_admin` | boolean | No | Describes if the user is a team admin. |

