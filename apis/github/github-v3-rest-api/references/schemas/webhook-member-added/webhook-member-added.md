# webhook-member-added

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: added | Yes |  |
| `changes` | object | No |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `member` | [webhooks_user](webhooks-user.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `permission` | object | No | This field is included for legacy purposes; use the `role_name` field instead. The `maintain`
role is mapped to `write` and the `triage` role is mapped to `read`. To determine the role
assigned to the collaborator, use the `role_name` field instead, which will provide the full
role name, including custom roles. |
| `role_name` | object | No | The role assigned to the collaborator. |

#### `changes.permission`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `to` | enum: write, admin, read | Yes |  |

#### `changes.role_name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `to` | string | Yes |  |

