# branch-with-protection

Branch With Protection

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `commit` | [commit](commit.md) | Yes |  |
| `_links` | object | Yes |  |
| `protected` | boolean | Yes |  |
| `protection` | [branch-protection](branch-protection.md) | Yes |  |
| `protection_url` | string (uri) | Yes |  |
| `pattern` | string | No |  |
| `required_approving_review_count` | integer | No |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html` | string | Yes |  |
| `self` | string (uri) | Yes |  |

