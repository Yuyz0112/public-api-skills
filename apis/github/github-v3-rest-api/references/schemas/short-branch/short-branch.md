# short-branch

Short Branch

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `commit` | object | Yes |  |
| `protected` | boolean | Yes |  |
| `protection` | [branch-protection](branch-protection.md) | No |  |
| `protection_url` | string (uri) | No |  |

## Nested Fields

### `commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |

