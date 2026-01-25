# iam_member_with_policies

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | [iam_email](iam-email.md) | No |  |
| `id` | [iam_membership_components-schemas-identifier](iam-membership-components-schemas-identifier.md) | No |  |
| `policies` | iam_list_member_policy[] | No | Access policy for the membership |
| `roles` | iam_role[] | No | Roles assigned to this Member. |
| `status` | enum: accepted, pending | No | A member's status in the account. |
| `user` | object | No | Details of the user associated to the membership. |

## Nested Fields

### `user`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | [iam_email](iam-email.md) | Yes |  |
| `first_name` | [iam_first_name](iam-first-name.md) | No |  |
| `id` | [iam_common_components-schemas-identifier](iam-common-components-schemas-identifier.md) | No |  |
| `last_name` | [iam_last_name](iam-last-name.md) | No |  |
| `two_factor_authentication_enabled` | [iam_two_factor_authentication_enabled](iam-two-factor-authentication-enabled.md) | No |  |

