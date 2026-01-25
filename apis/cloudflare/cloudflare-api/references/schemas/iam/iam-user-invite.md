# iam_user_invite

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expires_on` | [iam_schemas-expires_on](iam-schemas-expires-on.md) | No |  |
| `id` | [iam_invite_components-schemas-identifier](iam-invite-components-schemas-identifier.md) | No |  |
| `invited_by` | [iam_invited_by](iam-invited-by.md) | No |  |
| `invited_member_email` | [iam_invited_member_email](iam-invited-member-email.md) | No |  |
| `invited_member_id` | string | Yes | ID of the user to add to the organization. |
| `invited_on` | [iam_invited_on](iam-invited-on.md) | No |  |
| `organization_id` | string | Yes | ID of the organization the user will be added to. |
| `organization_is_enforcing_twofactor` | boolean | No |  |
| `organization_name` | string | No | Organization name. |
| `roles` | [iam_role_names](iam-role-names.md) | No |  |
| `status` | enum: pending, accepted, rejected... | No | Current status of the invitation. |

