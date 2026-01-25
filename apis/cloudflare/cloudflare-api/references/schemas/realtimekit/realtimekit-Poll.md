# realtimekit_Poll

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `anonymous` | boolean | No |  |
| `created_by` | string | No |  |
| `hide_votes` | boolean | No |  |
| `id` | string | Yes | ID of the poll |
| `options` | object[] | Yes | Answer options |
| `question` | string | Yes | Question asked by the poll |
| `voted` | string[] | No |  |

## Nested Fields

### `options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | number | Yes |  |
| `text` | string | Yes | Text of the answer option |
| `votes` | object[] | Yes |  |

#### `options.votes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `name` | string | Yes |  |

