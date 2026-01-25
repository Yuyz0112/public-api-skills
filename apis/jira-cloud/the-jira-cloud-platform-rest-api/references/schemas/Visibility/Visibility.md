# Visibility

The group or role to which this item is visible.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `identifier` | string | No | The ID of the group or the name of the role that visibility of this item is restricted to. |
| `type` | enum: group, role | No | Whether visibility of this item is restricted to a group or role. |
| `value` | string | No | The name of the group or role that visibility of this item is restricted to. Please note that the name of a group is mutable, to reliably identify a group use `identifier`. |

