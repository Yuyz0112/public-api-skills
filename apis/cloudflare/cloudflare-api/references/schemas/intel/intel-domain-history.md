# intel_domain-history

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `categorizations` | object[] | No |  |
| `domain` | [intel_domain_name](intel-domain-name.md) | No |  |

## Nested Fields

### `categorizations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `categories` | object[] | No |  |
| `end` | string (date) | No |  |
| `start` | string (date) | No |  |

#### `categorizations.categories`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `name` | string | No |  |

