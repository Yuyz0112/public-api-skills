# iam_create-member-with-roles

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | [iam_email](iam-email.md) | Yes |  |
| `roles` | iam_role_components-schemas-identifier[] | Yes | Array of roles associated with this member. |
| `status` | enum: accepted, pending | No |  |

