# iam_create-member-with-policies

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | [iam_email](iam-email.md) | Yes |  |
| `policies` | iam_create_member_policy[] | Yes | Array of policies associated with this member. |
| `status` | enum: accepted, pending | No |  |

