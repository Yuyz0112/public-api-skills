# iam_user_group

A group of policies resources.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_on` | string (date-time) | Yes | Timestamp for the creation of the user group |
| `id` | [iam_user_group_identifier](iam-user-group-identifier.md) | Yes |  |
| `modified_on` | string (date-time) | Yes | Last time the user group was modified. |
| `name` | string | Yes | Name of the user group. |
| `policies` | any[] | No | Policies attached to the User group |

