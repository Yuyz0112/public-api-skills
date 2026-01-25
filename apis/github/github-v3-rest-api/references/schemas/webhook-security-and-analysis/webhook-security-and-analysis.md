# webhook-security-and-analysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `changes` | object | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [full-repository](full-repository.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | No |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | object | No |  |

#### `changes.from`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `security_and_analysis` | [security-and-analysis](security-and-analysis.md) | No |  |

