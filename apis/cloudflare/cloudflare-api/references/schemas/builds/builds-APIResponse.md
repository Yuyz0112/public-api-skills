# builds_APIResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | object[] | Yes |  |
| `messages` | string[] | Yes |  |
| `result` | object | Yes |  |
| `result_info` | [builds_PaginationInfo](builds-PaginationInfo.md) | No |  |
| `success` | boolean | Yes |  |

## Nested Fields

### `errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | integer | No |  |
| `message` | string | No |  |

