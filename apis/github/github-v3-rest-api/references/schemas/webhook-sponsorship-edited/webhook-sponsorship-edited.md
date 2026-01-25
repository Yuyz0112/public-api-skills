# webhook-sponsorship-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `sponsorship` | [webhooks_sponsorship](webhooks-sponsorship.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `privacy_level` | object | No |  |

#### `changes.privacy_level`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The `edited` event types include the details about the change when someone edits a sponsorship to change the privacy. |

