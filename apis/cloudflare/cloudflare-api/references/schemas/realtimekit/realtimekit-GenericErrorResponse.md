# realtimekit_GenericErrorResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `error` | object | Yes |  |
| `success` | boolean | Yes | Success status of the request. |

## Nested Fields

### `error`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | number | Yes | HTTP status code of the error. |
| `message` | string | Yes | Error message describing what went wrong. |

