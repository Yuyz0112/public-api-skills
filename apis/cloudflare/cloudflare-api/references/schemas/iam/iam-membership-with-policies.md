# iam_membership-with-policies

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | [iam_schemas-account](iam-schemas-account.md) | No |  |
| `api_access_enabled` | [iam_api_access_enabled](iam-api-access-enabled.md) | No |  |
| `id` | [iam_membership_components-schemas-identifier](iam-membership-components-schemas-identifier.md) | No |  |
| `permissions` | any | No | All access permissions for the user at the account. |
| `policies` | iam_list_member_policy[] | No | Access policy for the membership |
| `roles` | [iam_role_names](iam-role-names.md) | No |  |
| `status` | [iam_schemas-status](iam-schemas-status.md) | No |  |

