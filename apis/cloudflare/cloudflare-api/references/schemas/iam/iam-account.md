# iam_account

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_on` | string (date-time) | No | Timestamp for the creation of the account |
| `id` | [iam_common_components-schemas-identifier](iam-common-components-schemas-identifier.md) | Yes |  |
| `managed_by` | object | No | Parent container details |
| `name` | string | Yes | Account name |
| `settings` | object | No | Account settings |
| `type` | [iam_account-type](iam-account-type.md) | Yes |  |

## Nested Fields

### `managed_by`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parent_org_id` | string | No | ID of the parent Organization, if one exists |
| `parent_org_name` | string | No | Name of the parent Organization, if one exists |

### `settings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `abuse_contact_email` | string | No | Sets an abuse contact email to notify for abuse reports. |
| `enforce_twofactor` | boolean | No | Indicates whether membership in this account requires that
Two-Factor Authentication is enabled |

