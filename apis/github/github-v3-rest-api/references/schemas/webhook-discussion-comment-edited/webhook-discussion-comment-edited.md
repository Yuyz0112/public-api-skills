# webhook-discussion-comment-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | Yes |  |
| `comment` | [webhooks_comment](webhooks-comment.md) | Yes |  |
| `discussion` | [discussion](discussion.md) | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `body` | object | Yes |  |

#### `changes.body`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |

