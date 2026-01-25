# CustomFieldMembershipCompact

This object describes a user or team's membership to a custom field including their level of access (Admin, Editor, or User).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `resource_subtype` | string | No | Type of the membership. |
| `parent` | [CustomFieldCompact](CustomFieldCompact.md) | No |  |
| `member` | [MemberCompact](MemberCompact.md) | No |  |
| `access_level` | enum: admin, editor, user | No | Whether the member has admin, editor, or user access to the custom field. |

