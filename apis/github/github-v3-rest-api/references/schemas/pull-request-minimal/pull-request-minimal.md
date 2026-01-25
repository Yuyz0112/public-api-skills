# pull-request-minimal

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `number` | integer | Yes |  |
| `url` | string | Yes |  |
| `head` | object | Yes |  |
| `base` | object | Yes |  |

## Nested Fields

### `head`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ref` | string | Yes |  |
| `sha` | string | Yes |  |
| `repo` | object | Yes |  |

#### `head.repo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `url` | string | Yes |  |
| `name` | string | Yes |  |

### `base`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ref` | string | Yes |  |
| `sha` | string | Yes |  |
| `repo` | object | Yes |  |

#### `base.repo`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `url` | string | Yes |  |
| `name` | string | Yes |  |

