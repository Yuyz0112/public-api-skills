# GetPermissionHolderResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: Group, AccountId | Yes | The permission holder type. This is "Group" or "AccountId". |
| `value` | string | Yes | The permission holder value. This is a group name if the type is "Group" or an account ID if the type is "AccountId". |

