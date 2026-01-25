# cache-purge_api-response-single-id

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | [cache-purge_messages](cache-purge-messages.md) | Yes |  |
| `messages` | [cache-purge_messages](cache-purge-messages.md) | Yes |  |
| `result` | object | No |  |
| `success` | boolean | Yes | Indicates the API call's success or failure. |

## Nested Fields

### `result`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [cache-purge_identifier](cache-purge-identifier.md) | Yes |  |

