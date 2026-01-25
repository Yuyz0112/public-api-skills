# repository-rule-violation-error

Repository rule violation was detected

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No |  |
| `documentation_url` | string | No |  |
| `status` | string | No |  |
| `metadata` | object | No |  |

## Nested Fields

### `metadata`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `secret_scanning` | object | No |  |

#### `metadata.secret_scanning`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bypass_placeholders` | object[] | No |  |

