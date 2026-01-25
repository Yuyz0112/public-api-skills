# realtimekit_ErrorResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `error` | object | Yes | Object containing details of the error that occurred |
| `success` | boolean | Yes | Whether the operation succeeded or not |

## Nested Fields

### `error`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | number | Yes | Error code |
| `message` | string | Yes | Error message |

